
# Type: node annotation change


A node change where the change alters node properties/annotations. TODO

URI: [ocl:NodeAnnotationChange](http://w3id.org/oclNodeAnnotationChange)


![img](http://yuml.me/diagram/nofunky;dir:TB/class/[NodeChange],[NodeAnnotationReplacement],[NodeAnnotationChange&#124;about(i):string%20%3F;old_value(i):string%20%3F;new_value(i):string%20%3F]^-[NodeAnnotationReplacement],[NodeChange]^-[NodeAnnotationChange],[Activity])

## Parents

 *  is_a: [NodeChange](NodeChange.md) - A simple change where the change is about a node

## Children

 * [NodeAnnotationReplacement](NodeAnnotationReplacement.md) - A node annotation change where the change replaces a particular property value. TODO

## Referenced by class


## Attributes


### Inherited from node change:

 * [new value](new_value.md)  <sub>OPT</sub>
    * Description: The value of a property held in the old instance of the ontology
    * range: [String](types/String.md)
 * [node change➞about](node_change_about.md)  <sub>OPT</sub>
    * range: [String](types/String.md)
 * [old value](old_value.md)  <sub>OPT</sub>
    * Description: The value of a property held in the old instance of the ontology
    * range: [String](types/String.md)
 * [was generated by](was_generated_by.md)  <sub>OPT</sub>
    * range: [Activity](Activity.md)
