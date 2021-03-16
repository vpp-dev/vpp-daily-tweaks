  - Started at Tue Mar 16 06:36:31 UTC 2021
    - Running tweak 000-do-test-refresh-deps...
```
Found something to submit after 000-do-test-refresh-deps:
* ayourtch-000-do-test-refresh-deps
  master
diff --git a/test/requirements-3.txt b/test/requirements-3.txt
index c25ac86c1..109baec14 100644
--- a/test/requirements-3.txt
+++ b/test/requirements-3.txt
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
  - Last done at Tue Mar 16 06:37:08 UTC 2021
