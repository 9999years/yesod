## 1.6.0.2

* Replace deprecated decodeFile with decodeFileEither. This should have no semantic impact, but silences a deprecation warning. [#1658](https://github.com/yesodweb/yesod/pull/1658)

## 1.6.0.1

* Remove unnecessary deriving of Typeable

## 1.6.0

* Upgrade to yesod-core 1.6

## 1.4.5

* Fix warnings

## 1.4.4

* Reduce dependencies

## 1.4.3.1

*  Handle exceptions while writing a file in `addStaticContentExternal`

## 1.4.3

* Switch to `Data.Yaml.Config`

## 1.4.2

* Do not parse string environment variables into numbers/booleans [#1061](https://github.com/yesodweb/yesod/issues/1061)

## 1.4.1

Provide the `Yesod.Default.Config2` module, for use by newer scaffoldings.
