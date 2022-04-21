# Corgi

Corgi is an _unbundled_ Emacs configuration primarily aimed at Clojure
developers. It is inspired by Spacemacs, but has a fraction of the footprint.

With Corgi you take back control of your Emacs config. You decide which Corgi
packages you want to load, the rest of the config is up to you, and Corgi itself
is lean enough that it's still possible to read and understand every line in an
afternoon.

Corgi relies on the [straight.el] functional package manager for reproducible
installs. Under the `corgi-emacs` Github organization you'll find:

- [corgi-emacs/corgi](https://github.com/corgi-emacs/corgi): Documentation and sample config
- [corgi-emacs/corgi-packages](https://github.com/corgi-emacs/corgi-packages): Straight.el package repo providing the various Corgi packages and meta-packages
- [corgi-emacs/corkey](https://github.com/corgi-emacs/corkey): Corgi's keybinding system, Corgi's most defining feature

And various other packages that together provide the Corgi experience.

- [clj-ns-name](https://github.com/corgi-emacs/clj-ns-name): Rename buffers according to their Clojure namespace name 
- [walkclj](https://github.com/corgi-emacs/walkclj): Convenience API to traverse parseclj results, used by clj-ns-name, based on [treepy](https://github.com/volrath/treepy.el) 

<!-- - [pprint-to-buffer](https://github.com/plexus/plexmacs/blob/master/pprint-to-buffer/pprint-to-buffer.el): Like cider-pprint-eval-last-sexp, but for Emacs Lisp (`, e p` in Corgi) (in plexmacs) -->
<!-- - [corgi-stateline](https://github.com/lambdaisland/corgi-packages/tree/main/corgi-stateline): Change the modeline color to indicate the current evil state -->
<!-- - [corgi-cider-indicator](https://github.com/lambdaisland/corgi-packages/blame/461d3f512073a146f6c6057d9ef1e74628e67590/corgi-clojure/corgi-cider-connection-indicator.el) Currently still lumped in with corgi-clojure but I'm splitting this out. Add a colored indicator to the modeline for each connected REPL that evaluations in the current buffer go to, indicating if it's clj/cljs/bb, and showing project/host/port if different from the current project. -->
<!-- - [cider-eval-pprint-register](https://github.com/lambdaisland/corgi-packages/blob/461d3f512073a146f6c6057d9ef1e74628e67590/corgi-clojure/corgi-clojure-cider-extras.el#L133-L160) Just a single function and currently lumped in with clojure-mode, but generally useful. Could perhaps also go upstream to CIDER if they'll take it. -->
