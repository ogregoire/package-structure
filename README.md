# package-structure

## Framework / libraries

Group by feature

    be.ogregoire.common.foo.feature1
    be.ogregoire.common.foo.feature2
    be.ogregoire.common.bar.feature1

## Applications

Group by feature

`<rev-domain>.<app>?.<app-name>.("common"|<feature-name>).<subfeature-name>.<sub-subfeature-name>`

    be.ogregoire.app.foo
    be.ogregoire.bar.common
    be.ogregoire.bar.feature1
      + Entity
      + Service
      + Resource (REST)
      + Validation
      - Preferably no DAO
      + ...
    be.ogregoire.bar.feature1.ui
    be.ogregoire.bar.feature2
    be.ogregoire.bar.feature3
    be.ogregoire.bar.feature3.ui
