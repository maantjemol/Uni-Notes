---
title: "virtualisation"
---

# virtualisation
**course:**
## Definition
Jobs of the [[virtualisation]] layer in the [[operating system]]:
**Processes** that are running on your device. These [[process]]es have:
- process context and state 
- execution policies (makes sure processes don't interfere with each other)
**Sharing cpu:**
- Time is shared between the multiple processes.
- [[Context switching]]
- [[Scheduling policies]]
**Sharing [[memory]]:**
- [[Address space]]: A part of memory a proces gets to use. When proces A gets an address space it cannot use or change anything outside it's address space. When A needs more space the address space can be expanded by the [[operating system]]. A gets a local address in memory. The conversion between local memory and general memory is called address translation. 
- [[Segmentation]]: when there is not enough space to put 2 blocks of memory after each other the [[operating system]] will use segmentation to use 2 different blocks. localy these blocks will be consecutive but for the [[operating system]] these blocks are not after each other and they need to get mapped to diffrent parts. Segmentation is slow so it's best to use it as little as possible.
- [[Paging]]: 
	- Smaller blocks in the memory blocks. When proces A wants a spefic part of memory it needs to request the whole page.
- diffrent types of memory: [[registers]], [[cache]], [[RAM]]:
	- Cache and memory are often swapped when a process needs them. When A needs to access [[RAM]] the [[operating system]] swaps it to [[cache]] for the proces to use. 
- What to do when memory is full? 
	- The part of memory that is not used gets saved to the harddrive. This is saved in pages. 
- Hierarchy from slow to fast: Harddrive, [[RAM]], [[cache]], [[registers]]  
## Backlinks

## Refrences:

---
Tags: #Concept #virtualisation #Uni 