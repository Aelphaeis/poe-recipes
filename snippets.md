# Snippets

## Alteration Spam
### Prefix Hunt

Search for `prefix_modifier` and replace with the modifier you're seeking
Search for `external_node` and replace with the external node to connect with
```mermaid
flowchart TD
  subgraph alt_spam[" "]
    transmutation["Orb of Transmutation"] --> open_prefix{Has open Prefix?}
    open_prefix --> |Yes| augmentation["Orb of Augmentation"]
    open_prefix --> |No| magic_prefix_check{prefix_modifier ?}
    augmentation --> magic_prefix_check
    magic_prefix_check --> |No| alteration["Orb of alteration"]
    alteration --> |No| open_prefix
  end
magic_prefix_check --> |yes| external_node["External Node"]




