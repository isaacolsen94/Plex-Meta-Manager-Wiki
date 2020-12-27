The script requires a Metadata File per Library defined in the Configuration File.

If the Metadata File location is not specified it will look in the same directory as the Configuration File for a YAML file whose name matches the mapped name of the library in the Configuration File.

There are only two mappings allowed in the Metadata File's root:
| Name | Attribute | Description |
| :-- | :-- | :-- |
| [Metadata](https://github.com/meisnate12/Plex-Meta-Manager/wiki/Metadata-Attributes) | `metadata` | mapping where metadata changes go |
| [Collections](https://github.com/meisnate12/Plex-Meta-Manager/wiki/Collection-Attributes) | `collections` | mapping where automatic collections and collection metdata go |

* Either `metadata` or `collections` is required in order to run.