deficiency components
----------------------

This is a curated listing of biojs.io components with a deficiencies like
If you see a component that doesn't fullfil BioJS, please add it here.

Categories
-----------

* incomplete API documentation (`sparse_doc`)
* no unit testing (`no_tests`)
* no snippets (`no_snippets`)
* lack of events to interact with (`sparse_events`)
* no answering github issues (`inactive_on_github`)

If you add a new category, you also need to add it to the registry.

FAQ
----

### I improved my component - how can I remove the negative badge?

Just make a pull request to this repository and within remove your component from 
the list.

### How can I report or tag a component?

Just add a new entry to our [list][list] - only the categories listed above are valid.

1. Pick tags from the above categories
2. Add it to the end of the [YAML](https://en.wikipedia.org/wiki/YAML) [list][list]

Here is a mini guide for YAML:

```
horrible_component: 
  - item_1
  - item_2
```

(The items use two spaces)

### I want to tag components, but I fear that people can get mad at me.

You don't need to be afraid - most of the authors of the deficiency components
have vanished anyway and if they are still active they are grateful for your work.


TODO
----

* send an automatic email to the package authors when their packages has been tagged

[list]: list.yaml

License
--------

"THE COMMUNITY BEER-WARE LICENSE" 

This file is part of a community effort to improve BioJS.
As long as you retain this notice you can do whatever you want with this stuff.
If you meet some day with one of the contributors, and you think their contribution
is worth it, you can buy them a beer (or orange juice) in return.
