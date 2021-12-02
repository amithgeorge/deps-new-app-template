# com.amithgeorge/app-template

## Usage

Assuming you have installed `deps-new` as your `new` "tool" via:

```shell
clojure -Ttools install io.github.seancorfield/deps-new '{:git/tag "v0.4.3"}' :as new
```

Execute

```shell
clojure -Sdeps '{:deps {com.amithgeorge/app-template {:git/sha "0c729e916609702f74ddbd01940f573730c4f65f", :git/url "https://github.com/amithgeorge/deps-new-app-template.git"}}}' -Tnew create :template com.amithgeorge/app-template :name test-app
```
