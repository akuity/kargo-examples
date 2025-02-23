In this example, a Warehouse monitors changes to a single YAML file in git.
Specific contents of that file can be parsed using `yaml-parse` and then
promoted into another file using `yaml-update`.

NOTE: this example uses YAML, but support for JSON is also supported using
the `json-parse` and `json-update` steps.