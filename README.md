# kit-ninja
Knowit Ninja project

Available handlebar helpers:

```bash

{{#times 1}}
{{/times}}

{{lipsum 1}}

{{lipsumtitle}}

{{cat}}

{{claude}}

{{addClasses "page-article" page-name}}

{{#if_eq page-name 'page-local-contact'}}
{{else}}
{{/if_eq}}

{{{showSubmenus has-submenu}}}

{{#ifCond var1 '==' var2}}, {{#ifCond var1 '!=' var2}} etc.

{{>myPartial id=(concat "foo" myVar myOtherVar)}}

```
