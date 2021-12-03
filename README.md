# com.amithgeorge/app-template

## Usage

Assuming you have installed `deps-new` as your `new` "tool" via:

```shell
clojure -Ttools install io.github.seancorfield/deps-new '{:git/tag "v0.4.3"}' :as new
```

Execute

```shell
clojure -Sdeps '{:deps {com.amithgeorge/app-template {:git/sha "59c7960cd3b0dd678b161ae7902a5ca017333708", :git/url "https://github.com/amithgeorge/deps-new-app-template.git"}}}' -Tnew create :template com.amithgeorge/app-template :name com.example/test-app
```

This will create a repo with src files at the paths

- src/com/example/test_app/main.clj
- src/com/example/test_app/test_app.clj

## Dev

Execute

```shell
clojure -Sdeps '{:deps {com.amithgeorge/app-template {:local/root "./app-template"}}}' -Tnew create :template com.amithgeorge/app-template :name com.example/test-app
```
