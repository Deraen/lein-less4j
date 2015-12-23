# lein-less4j
[![Clojars Project](http://clojars.org/deraen/lein-less4j/latest-version.svg)](http://clojars.org/deraen/lein-less4j)

# [Moved to Deraen/less4clj](https://github.com/Deraen/less4clj)

Leiningen task to compile Less.

* Provides the `less4j` task
* For each `.main.less` in source-dirs creates equivalent `.css` file.
* Uses [Less4j](https://github.com/SomMeri/less4j) Java implementation of Less compiler through [less4clj clojure wrapper](https://github.com/Deraen/less4clj)
* For parallel [boot-clj](http://boot-clj.com/) task check [boot-less](https://github.com/Deraen/boot-less/)
* For parallel [sass](http://sass-lang.com/) task check [lein-sass4clj](https://github.com/Deraen/lein-sass4clj)

## Usage

```clj
:less {:source-paths ["src/less"]
       :target-path "target/generated/public/css"
       :source-map true
       :compression true}
```

## License

Copyright © 2015 Juho Teperi

Distributed under the Eclipse Public License either version 1.0 or (at your option) any later version.
