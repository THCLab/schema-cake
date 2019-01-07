# DID Spec "2.0"

Idea to use DID concept in much broader way then is it right now defined in https://w3c-ccg.github.io/did-spec/

The idea is to define DID as a global decentralize identifier which can be resolove to different types of DID, to name few:

* DID as a a unit of control `did-key:sov:12312515124124`
  Resolve to the did document which is currently defined within official DID spec but in very limited way. Just for purpose of resolving the keys (prove control over that did).
* DID as a a unit of language `did-schema:sov:1231415124151`, `did-overlay:sov:13215512312`, `did-schema-element:sov:5814108410924`
  Resolve to the did document which specify schema base or overlays. Used to compose to schema object.

