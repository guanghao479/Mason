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

## Snippets [trigger: details]

__args: <%args> block__

```perl
<%args>
  ${1} => ${2}
</%args>
```

__class: <%class> block__

```perl
<%class>
  ${1}
</%class>
```

__comp: <& &> tag__

```perl
<& "${1}"${2:, "$3" => $4} &>
```

__def: <%def> block__

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

__doc: <%doc> block__

```perl
<%doc>
  ${1}
</%doc>
```

__init: <%init> block__

```perl
<%init>
  ${1}
</%init>
```

__mcomp: $m->comp()__

```perl
$m->comp("${1}"${2:, "$3" => $4});
```

__method: <%method> block__

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

__once: <%once> block__

```perl
<%once>
  ${1}
</%once>
```

__perl: <%perl> block__

```perl
<%perl>
  ${1}
</%perl>
```
