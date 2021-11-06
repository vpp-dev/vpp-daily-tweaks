  - Started at Sat Nov  6 06:34:23 UTC 2021
    - Running tweak 000-do-test-refresh-deps...
```
Found something to submit after 000-do-test-refresh-deps:
* ayourtch-000-do-test-refresh-deps
  master
diff --git a/test/requirements-3.txt b/test/requirements-3.txt
index 654f98f1c..9e371b453 100644
--- a/test/requirements-3.txt
+++ b/test/requirements-3.txt
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
-jsonschema==4.1.2 \
-    --hash=sha256:166870c8ab27bd712a8627e0598de4685bd8d199c4d7bd7cacc3d941ba0c6ca0 \
-    --hash=sha256:5c1a282ee6b74235057421fd0f766ac5f2972f77440927f6471c9e8493632fac
+jsonschema==4.2.1 \
+    --hash=sha256:2a0f162822a64d95287990481b45d82f096e99721c86534f48201b64ebca6e8c \
+    --hash=sha256:390713469ae64b8a58698bb3cbc3859abe6925b565a973f87323ef21b09a27a8
     # via -r requirements.txt
 lark-parser==0.6.7 \
     --hash=sha256:062800f3823a6c733ec1d181a2089a22d1f62dbe65f90a3f6b1e6de1934b05ef
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
  - Last done at Sat Nov  6 06:34:55 UTC 2021
