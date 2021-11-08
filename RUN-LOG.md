  - Started at Mon Nov  8 06:36:04 UTC 2021
    - Running tweak 000-do-test-refresh-deps...
```
Found something to submit after 000-do-test-refresh-deps:
* ayourtch-000-do-test-refresh-deps
  master
diff --git a/test/requirements-3.txt b/test/requirements-3.txt
index 785782345..7f3e8674f 100644
--- a/test/requirements-3.txt
+++ b/test/requirements-3.txt
@@ -119,9 +119,9 @@ docutils==0.17.1 \
     #   recommonmark
     #   sphinx
     #   sphinx-rtd-theme
-graphviz==0.17 \
-    --hash=sha256:5dadec94046d82adaae6019311a30e0487536d9d5a60d85451f0ba32f9fc6559 \
-    --hash=sha256:ef6e2c5deb9cdcc0c7eece1d89625fd07b0f2208ea2bcb483520907ddf8b4e12
+graphviz==0.18 \
+    --hash=sha256:0f04e5f939d3a839b524283d590e941892c56e75e60e0f5238c431264f490022 \
+    --hash=sha256:f8bab3bf3eda40ab259bb96f786811b5dec6fd6957fa70a5b1977534e1ee2a40
     # via objgraph
 idna==3.3 \
     --hash=sha256:84d9dd047ffa80596e0f246e2eab0b391788b0503584e8945f2368256d2735ff \
@@ -131,13 +131,17 @@ imagesize==1.2.0 \
     --hash=sha256:6965f19a6a2039c7d48bca7dba2473069ff854c36ae6f19d2cde309d998228a1 \
     --hash=sha256:b1f6b5a4eab1f73479a50fb79fcf729514a900c341d8503d62a62dbc4127a2b1
     # via sphinx
+importlib-resources==5.4.0 \
+    --hash=sha256:33a95faed5fc19b4bc16b29a6eeae248a3fe69dd55d4d229d2b480e23eeaad45 \
+    --hash=sha256:d756e2f85dd4de2ba89be0b21dba2a3bbec2e871a42a3a16719258a11f87506b
+    # via jsonschema
 jinja2==3.0.2 \
     --hash=sha256:827a0e32839ab1600d4eb1c4c33ec5a8edfbc5cb42dafa13b81f182f97784b45 \
     --hash=sha256:8569982d3f0889eed11dd620c706d39b60c36d6d25843961f33f77fb6bc6b20c
     # via sphinx
-jsonschema==4.1.2 ; python_version >= "3.7" \
-    --hash=sha256:166870c8ab27bd712a8627e0598de4685bd8d199c4d7bd7cacc3d941ba0c6ca0 \
-    --hash=sha256:5c1a282ee6b74235057421fd0f766ac5f2972f77440927f6471c9e8493632fac
+jsonschema==4.2.1 ; python_version >= "3.7" \
+    --hash=sha256:2a0f162822a64d95287990481b45d82f096e99721c86534f48201b64ebca6e8c \
+    --hash=sha256:390713469ae64b8a58698bb3cbc3859abe6925b565a973f87323ef21b09a27a8
     # via -r requirements.txt
 lark-parser==0.6.7 \
     --hash=sha256:062800f3823a6c733ec1d181a2089a22d1f62dbe65f90a3f6b1e6de1934b05ef
@@ -281,9 +285,9 @@ pycodestyle==2.8.0 \
     --hash=sha256:720f8b39dde8b293825e7ff02c475f3077124006db4f440dcbc9a20b76548a20 \
     --hash=sha256:eddd5847ef438ea1c7870ca7eb78a9d47ce0cdb4851a5523949f2601d0cbbe7f
     # via -r requirements.txt
-pycparser==2.20 \
-    --hash=sha256:2d475327684562c3a96cc71adf7dc8c4f0565175cf86b6d7a404ff4c771f15f0 \
-    --hash=sha256:7582ad22678f0fcd81102833f60ef8d0e57288b6b5fb00323d101be910e35705
+pycparser==2.21 \
+    --hash=sha256:8ee45429555515e1f6b185e78100aea234072576aa43ab53aefcae078162fca9 \
+    --hash=sha256:e644fdec12f7872f86c58ff790da456218b10f863970249516d60a5eaca77206
     # via cffi
 pyenchant==3.2.2 \
     --hash=sha256:1cf830c6614362a78aab78d50eaf7c6c93831369c52e1bb64ffae1df0341e637 \
@@ -439,6 +443,10 @@ wheel==0.37.0 \
     --hash=sha256:21014b2bd93c6d0034b6ba5d35e4eb284340e09d63c59aef6fc14b0f346146fd \
     --hash=sha256:e2ef7239991699e3355d54f8e968a21bb940a1dbf34a4d226741e64462516fad
     # via pip-tools
+zipp==3.6.0 \
+    --hash=sha256:71c644c5369f4a6e07636f0aa966270449561fcea2e3d6747b8d23efaa9d7832 \
+    --hash=sha256:9fe5ea21568a0a70e50f273397638d39b03353731e6cbbb3fd8502a33fec40bc
+    # via importlib-resources
 
 # WARNING: The following packages were not pinned, but pip requires them to be
 # pinned when the requirements file includes hashes. Consider using the --allow-unsafe flag.
```
  - Last done at Mon Nov  8 06:36:39 UTC 2021
