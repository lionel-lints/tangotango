# TangoTango
An idea for a library and API for real-time document collaboration.

The primary idea for this library is that it is an api to aid real-time collaboration using different document editors (eg. slate, draftjs, quill etc).

The idea is that the operational transformation algorithm is abstracted into a meaningful api that provides async reconciliation.
Ideally this can be used beyond and outside simple document editors to include real time changes to games and other web based interactive contexts.



# Design Goals

1. Build an abstract interface for a client which implements the client side of OT.
1. Build an abscract interface for a server which implements the server side of OT.
1. Test the paradigm and extend it so that it is feasible to use under a few different contexts.

