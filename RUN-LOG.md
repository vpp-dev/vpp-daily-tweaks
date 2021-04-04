  - Started at Sun Apr  4 06:42:31 UTC 2021
    - Running tweak 000-do-test-refresh-deps...
```
Found something to submit after 000-do-test-refresh-deps:
* ayourtch-000-do-test-refresh-deps
  master
diff --git a/test/requirements-3.txt b/test/requirements-3.txt
index c25ac86c1..f15984e22 100644
--- a/test/requirements-3.txt
+++ b/test/requirements-3.txt
@@ -63,27 +63,27 @@ click==7.1.2 \
     --hash=sha256:d2b5255c7c6349bc1bd1e59e08cd12acbbd63ce649f2588755783aa94dfb6b1a \
     --hash=sha256:dacca89f4bfadd5de3d7489b7c8a566eee0d3676333fbb50030263894c38c0dc \
     # via pip-tools
-cryptography==3.4.6 \
-    --hash=sha256:066bc53f052dfeda2f2d7c195cf16fb3e5ff13e1b6b7415b468514b40b381a5b \
-    --hash=sha256:0923ba600d00718d63a3976f23cab19aef10c1765038945628cd9be047ad0336 \
-    --hash=sha256:2d32223e5b0ee02943f32b19245b61a62db83a882f0e76cc564e1cec60d48f87 \
-    --hash=sha256:4169a27b818de4a1860720108b55a2801f32b6ae79e7f99c00d79f2a2822eeb7 \
-    --hash=sha256:57ad77d32917bc55299b16d3b996ffa42a1c73c6cfa829b14043c561288d2799 \
-    --hash=sha256:5ecf2bcb34d17415e89b546dbb44e73080f747e504273e4d4987630493cded1b \
-    --hash=sha256:600cf9bfe75e96d965509a4c0b2b183f74a4fa6f5331dcb40fb7b77b7c2484df \
-    --hash=sha256:66b57a9ca4b3221d51b237094b0303843b914b7d5afd4349970bb26518e350b0 \
-    --hash=sha256:93cfe5b7ff006de13e1e89830810ecbd014791b042cbe5eec253be11ac2b28f3 \
-    --hash=sha256:9e98b452132963678e3ac6c73f7010fe53adf72209a32854d55690acac3f6724 \
-    --hash=sha256:df186fcbf86dc1ce56305becb8434e4b6b7504bc724b71ad7a3239e0c9d14ef2 \
-    --hash=sha256:fec7fb46b10da10d9e1d078d1ff8ed9e05ae14f431fdbd11145edd0550b9a964 \
+cryptography==3.4.7 \
+    --hash=sha256:0f1212a66329c80d68aeeb39b8a16d54ef57071bf22ff4e521657b27372e327d \
+    --hash=sha256:1e056c28420c072c5e3cb36e2b23ee55e260cb04eee08f702e0edfec3fb51959 \
+    --hash=sha256:240f5c21aef0b73f40bb9f78d2caff73186700bf1bc6b94285699aff98cc16c6 \
+    --hash=sha256:26965837447f9c82f1855e0bc8bc4fb910240b6e0d16a664bb722df3b5b06873 \
+    --hash=sha256:37340614f8a5d2fb9aeea67fd159bfe4f5f4ed535b1090ce8ec428b2f15a11f2 \
+    --hash=sha256:3d10de8116d25649631977cb37da6cbdd2d6fa0e0281d014a5b7d337255ca713 \
+    --hash=sha256:3d8427734c781ea5f1b41d6589c293089704d4759e34597dce91014ac125aad1 \
+    --hash=sha256:7ec5d3b029f5fa2b179325908b9cd93db28ab7b85bb6c1db56b10e0b54235177 \
+    --hash=sha256:8e56e16617872b0957d1c9742a3f94b43533447fd78321514abbe7db216aa250 \
+    --hash=sha256:de4e5f7f68220d92b7637fc99847475b59154b7a1b3868fb7385337af54ac9ca \
+    --hash=sha256:eb8cc2afe8b05acbd84a43905832ec78e7b3873fb124ca190f574dca7389a87d \
+    --hash=sha256:ee77aa129f481be46f8d92a1a7db57269a2f23052d5f2433b4621bb457081cc9 \
     # via -r requirements.txt, noiseprotocol
 deprecation==2.1.0 \
     --hash=sha256:72b3bde64e5d778694b0cf68178aed03d15e15477116add3fb773e581f9518ff \
     --hash=sha256:a10811591210e1fb0e768a8c25517cabeabcba6f0bf96564f8ff45189f90b14a \
     # via -r requirements.txt
-docutils==0.16 \
-    --hash=sha256:0c5b78adfbf7762415433f5515cd5c9e762339e23369dbe8000d84a4bf4ab3af \
-    --hash=sha256:c2de3a60e9e7d07be26b7f2b00ca0309c207e06c100f9cc2a94931fc75a478fc \
+docutils==0.17 \
+    --hash=sha256:a71042bb7207c03d5647f280427f14bfbd1a65c9eb84f4b341d85fafb6bb4bdf \
+    --hash=sha256:e2ffeea817964356ba4470efba7c2f42b6b0de0b04e66378507e3e2504bbff4c \
     # via sphinx
 graphviz==0.16 \
     --hash=sha256:3cad5517c961090dfc679df6402a57de62d97703e2880a1a46147bb0dc1639eb \
@@ -216,17 +216,17 @@ ptyprocess==0.7.0 \
     --hash=sha256:4b41f3967fce3af57cc7e94b888626c18bf37a083e3651ca8feeb66d492fef35 \
     --hash=sha256:5c5d0a3b48ceee0b48485e0c26037c0acd7d29765ca3fbb5cb3831d347423220 \
     # via pexpect
-pycodestyle==2.6.0 \
-    --hash=sha256:2295e7b2f6b5bd100585ebcb1f616591b652db8a741695b3d8f5d28bdc934367 \
-    --hash=sha256:c58a7d2815e0e8d7972bf1803331fb0152f867bd89adf8a01dfd55085434192e \
+pycodestyle==2.7.0 \
+    --hash=sha256:514f76d918fcc0b55c6680472f0a37970994e07bbb80725808c17089be302068 \
+    --hash=sha256:c389c1d06bf7904078ca03399a4816f974a1d590090fecea0c63ec26ebaf1cef \
     # via -r requirements.txt
 pycparser==2.20 \
     --hash=sha256:2d475327684562c3a96cc71adf7dc8c4f0565175cf86b6d7a404ff4c771f15f0 \
     --hash=sha256:7582ad22678f0fcd81102833f60ef8d0e57288b6b5fb00323d101be910e35705 \
     # via cffi
-pygments==2.8.0 \
-    --hash=sha256:37a13ba168a02ac54cc5891a42b1caec333e59b66addb7fa633ea8a6d73445c0 \
-    --hash=sha256:b21b072d0ccdf29297a82a2363359d99623597b8a265b8081760e4d0f7153c88 \
+pygments==2.8.1 \
+    --hash=sha256:2656e1a6edcdabf4275f9a3640db59fd5de107d88e8663c5d4e9a0fa62f77f94 \
+    --hash=sha256:534ef71d539ae97d4c3a4cf7d6f110f214b0e687e92f9cb9d2a3b0d3101289c8 \
     # via sphinx
 pympler==0.9 \
     --hash=sha256:f2cbe7df622117af890249f2dea884eb702108a12d729d264b7c5983a6e06e47 \
@@ -290,9 +290,9 @@ syslog-rfc5424-parser==0.3.2 \
     --hash=sha256:6134ee1958da89ab7f8d32ed5370a49ddabcc99d75a950b6ec59708417f20a7a \
     --hash=sha256:80a9239d4da404a271266000f4c5f00a183af3d03d53d19d7052c8272430bee9 \
     # via -r requirements.txt
-urllib3==1.26.3 \
-    --hash=sha256:1b465e494e3e0d8939b50680403e3aedaa2bc434b7d5af64dfd3c958d7f5ae80 \
-    --hash=sha256:de3eedaad74a2683334e282005cd8d7f22f4d55fa690a2a1020a416cb0a47e73 \
+urllib3==1.26.4 \
+    --hash=sha256:2f4da4594db7e1e110a944bb1b551fdf4e6c136ad42e4234131391e21eb5b0df \
+    --hash=sha256:e7b021f7241115872f92f43c6508082facffbd1c048e3c6e2bb9c2a157e28937 \
     # via requests
 
 # WARNING: The following packages were not pinned, but pip requires them to be
```
  - Last done at Sun Apr  4 06:43:08 UTC 2021
