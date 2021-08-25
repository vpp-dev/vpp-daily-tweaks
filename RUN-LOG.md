  - Started at Wed Aug 25 06:35:29 UTC 2021
    - Running tweak 000-do-test-refresh-deps...
```
Found something to submit after 000-do-test-refresh-deps:
* ayourtch-000-do-test-refresh-deps
  master
diff --git a/test/requirements-3.txt b/test/requirements-3.txt
index 161f09d2c..a924debbb 100644
--- a/test/requirements-3.txt
+++ b/test/requirements-3.txt
@@ -75,21 +75,24 @@ commonmark==0.9.1 \
     --hash=sha256:452f9dc859be7f06631ddcb328b6919c67984aca654e5fefb3914d54691aed60 \
     --hash=sha256:da2f38c92590f83de410ba1a3cbceafbc74fee9def35f9251ba9a971d6d66fd9
     # via recommonmark
-cryptography==3.4.7 \
-    --hash=sha256:0f1212a66329c80d68aeeb39b8a16d54ef57071bf22ff4e521657b27372e327d \
-    --hash=sha256:1e056c28420c072c5e3cb36e2b23ee55e260cb04eee08f702e0edfec3fb51959 \
-    --hash=sha256:240f5c21aef0b73f40bb9f78d2caff73186700bf1bc6b94285699aff98cc16c6 \
-    --hash=sha256:26965837447f9c82f1855e0bc8bc4fb910240b6e0d16a664bb722df3b5b06873 \
-    --hash=sha256:37340614f8a5d2fb9aeea67fd159bfe4f5f4ed535b1090ce8ec428b2f15a11f2 \
-    --hash=sha256:3d10de8116d25649631977cb37da6cbdd2d6fa0e0281d014a5b7d337255ca713 \
-    --hash=sha256:3d8427734c781ea5f1b41d6589c293089704d4759e34597dce91014ac125aad1 \
-    --hash=sha256:7ec5d3b029f5fa2b179325908b9cd93db28ab7b85bb6c1db56b10e0b54235177 \
-    --hash=sha256:8e56e16617872b0957d1c9742a3f94b43533447fd78321514abbe7db216aa250 \
-    --hash=sha256:b01fd6f2737816cb1e08ed4807ae194404790eac7ad030b34f2ce72b332f5586 \
-    --hash=sha256:bf40af59ca2465b24e54f671b2de2c59257ddc4f7e5706dbd6930e26823668d3 \
-    --hash=sha256:de4e5f7f68220d92b7637fc99847475b59154b7a1b3868fb7385337af54ac9ca \
-    --hash=sha256:eb8cc2afe8b05acbd84a43905832ec78e7b3873fb124ca190f574dca7389a87d \
-    --hash=sha256:ee77aa129f481be46f8d92a1a7db57269a2f23052d5f2433b4621bb457081cc9
+cryptography==3.4.8 \
+    --hash=sha256:0a7dcbcd3f1913f664aca35d47c1331fce738d44ec34b7be8b9d332151b0b01e \
+    --hash=sha256:1eb7bb0df6f6f583dd8e054689def236255161ebbcf62b226454ab9ec663746b \
+    --hash=sha256:21ca464b3a4b8d8e86ba0ee5045e103a1fcfac3b39319727bc0fc58c09c6aff7 \
+    --hash=sha256:34dae04a0dce5730d8eb7894eab617d8a70d0c97da76b905de9efb7128ad7085 \
+    --hash=sha256:3520667fda779eb788ea00080124875be18f2d8f0848ec00733c0ec3bb8219fc \
+    --hash=sha256:3fa3a7ccf96e826affdf1a0a9432be74dc73423125c8f96a909e3835a5ef194a \
+    --hash=sha256:5b0fbfae7ff7febdb74b574055c7466da334a5371f253732d7e2e7525d570498 \
+    --hash=sha256:8695456444f277af73a4877db9fc979849cd3ee74c198d04fc0776ebc3db52b9 \
+    --hash=sha256:94cc5ed4ceaefcbe5bf38c8fba6a21fc1d365bb8fb826ea1688e3370b2e24a1c \
+    --hash=sha256:94fff993ee9bc1b2440d3b7243d488c6a3d9724cc2b09cdb297f6a886d040ef7 \
+    --hash=sha256:9965c46c674ba8cc572bc09a03f4c649292ee73e1b683adb1ce81e82e9a6a0fb \
+    --hash=sha256:a00cf305f07b26c351d8d4e1af84ad7501eca8a342dedf24a7acb0e7b7406e14 \
+    --hash=sha256:a305600e7a6b7b855cd798e00278161b681ad6e9b7eca94c721d5f588ab212af \
+    --hash=sha256:cd65b60cfe004790c795cc35f272e41a3df4631e2fb6b35aa7ac6ef2859d554e \
+    --hash=sha256:d2a6e5ef66503da51d2110edf6c403dc6b494cc0082f85db12f54e9c5d4c3ec5 \
+    --hash=sha256:d9ec0e67a14f9d1d48dd87a2531009a9b251c02ea42851c060b25c782516ff06 \
+    --hash=sha256:f44d141b8c4ea5eb4dbc9b3ad992d45580c1d22bf5e24363f2fbf50c2d7ae8a7
     # via
     #   -r requirements.txt
     #   noiseprotocol
@@ -257,9 +260,9 @@ pyenchant==3.2.1 \
     --hash=sha256:5e206a1d6596904a922496f6c9f7d0b964b243905f401f5f2f40ea4d1f74e2cf \
     --hash=sha256:e8546c28b630f6d9f76642166656e337df2a1849cbef2b8ee198e7f64266f4ee
     # via sphinxcontrib-spelling
-pygments==2.9.0 \
-    --hash=sha256:a18f47b506a429f6f4b9df81bb02beab9ca21d0a5fee38ed15aef65f0545519f \
-    --hash=sha256:d66e804411278594d764fc69ec36ec13d9ae9147193a1740cd34d272ca383b8e
+pygments==2.10.0 \
+    --hash=sha256:b8e67fe6af78f492b3c4b3e2970c0624cbf08beb1e493b2c99b9fa1b67a20380 \
+    --hash=sha256:f398865f7eb6874156579fdf36bc840a03cab64d1cde9e93d68f46a425ec52c6
     # via sphinx
 pympler==0.9 \
     --hash=sha256:f2cbe7df622117af890249f2dea884eb702108a12d729d264b7c5983a6e06e47
```
  - Last done at Wed Aug 25 06:36:04 UTC 2021
