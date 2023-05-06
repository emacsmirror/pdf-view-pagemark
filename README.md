# pdf-view-pagemark

Show an indicator of the remaining text in PDF page.

## Demo

![](./pdf-view-pagemark-demo.gif)

## Installation

```elisp
(add-to-list 'load-path "<path-to-wraplish>")

(require 'pdf-view-pagemark)

(add-hook pdf-view-mode-hook 'pdf-view-pagemark-mode)
```

Or

```elisp

(use-package pdf-view-pagemark
  :after pdf-tools
  :load-path "~/.emacs.d/site-lisp/pdf-view-pagemark"
  :hook (pdf-view-mode . pdf-view-pagemark-mode))
```

## Contributors

<a href = "https://github.com/kimim/pdf-view-pagemark/graphs/contributors">
  <img src = "https://contrib.rocks/image?repo=kimim/pdf-view-pagemark"/>
</a>
