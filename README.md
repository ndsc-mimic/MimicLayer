MimicLayer
==========


MimicLayer is a new kind of security network hypervisor that enables dynamic structure via the deployment of multiple controller platforms in different programming languages. Our implementation is partially based on OpenVirteX, an typical scenario of network virtualization layer. Unlike with it, which statically config several tenant controllers and separate control by datapath virtualization. MimicNOS allows multiple controllers to cooperate on managing the same flows. This is similar with Covisor, another network hypervisor. However, MimicNOS introduces a scheduler so that it can dynamically select several controller platform to run in pararrel. there are several special components in MimiNOS.

* Heterogeneous controller set.
* Intelligent scheduler.
* Flow sink. 

to be appear soon......
