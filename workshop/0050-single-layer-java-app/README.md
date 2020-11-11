build the app locally
build the image using the single layer dockerfile
use dive to inspect the layers

discuss shortcomings of this approach

* security - hard to reason about
* giant layers replaced with each build
* network BW: giant layers from build env -> registry
* deployment BW: registry -> kubelet

