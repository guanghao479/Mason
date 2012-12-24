Mason
=====

Mason Syntax and Snippets for Sublime Text 2

## Install

Install via [Package Control](http://wbond.net/sublime_packages/package_control)

## File Types Supported

`.m`
`.mi`
`.mc`
`.md`
`autohandler`
`dhandler`
`mhtml`

## Symbols / Definitions

Any named block defined by <%def>, <%method> and <%closure>

## Snippets

__args__

```perl
<%args>
${1} => ${2}
</%args>
```

__class__

```perl
<%class>
${1}
</%class>
```

__<& &>__

```perl
<& "${1}"${2:, "$3" => $4} &>
```

__def__

```perl
<%def .${1}>
  <%args>
    ${2}
  </%args>

  <%perl>
    ${3}
  </%perl>
</%def>
```

__doc__

```perl
<%doc>
${1}
</%doc>
```

__init__

```perl
<%init>
${1}
</%init>
```

__$m->comp()__

```perl
$m->comp("${1}"${2:, "$3" => $4});
```

__method__

```perl
<%method ${1}>
  <%args>
    ${2}
  </%args>

  <%perl>
    ${3}
  </%perl>
</%method>
```

__once__

```perl
<%once>
  ${1}
</%once>
```

__perl__

```perl
<%perl>
  ${1}
</%perl>
```
