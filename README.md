**DarkScript Networking**
> 
You can create your own network mask while testing viruses on VirtualMaching so your own PC doesn't get infected

**Change Log 1.0.5**
>
Hey guys, the author here. I found an issue in the code. Here is the old code and how to fix it

**Old Piece of Code** : 
>
`let{`
>
 `networkname="YOUR NETWORK NAME HERE";`
 >
  `networkpass="NETWORK PASSWORD HERE";`
  >
  `networkip=[command.internal.networkAssignIP];`
  >
  `networkport=assignCustom(meetreq[=>199999,=<255575]);`
  >
  `}`
  >
**New, fixed version changed version**
> 1. Changed `import dastNetwork.HandleNetwork` to `import dastNetwork.NetworkHandle`
