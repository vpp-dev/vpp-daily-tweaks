  - Started at Tue Dec 21 06:36:40 UTC 2021
    - Running tweak 000-do-test-refresh-deps...
```
Found something to submit after 000-do-test-refresh-deps:
* ayourtch-000-do-test-refresh-deps
  master
diff --git a/test/requirements-3.txt b/test/requirements-3.txt
index 785782345..66b12483e 100644
--- a/test/requirements-3.txt
+++ b/test/requirements-3.txt
@@ -72,9 +72,9 @@ cffi==1.15.0 \
     --hash=sha256:fd8a250edc26254fe5b33be00402e6d287f562b6a5b2152dec302fa15bb3e997 \
     --hash=sha256:ffaa5c925128e29efbde7301d8ecaf35c8c60ffbcd6a1ffd3a552177c8e5e796
     # via cryptography
-charset-normalizer==2.0.7 \
-    --hash=sha256:e019de665e2bcf9c2b64e2e5aa025fa991da8720daa3c1138cadd2fd1856aed0 \
-    --hash=sha256:f7af805c321bfa1ce6714c51f254e0d5bb5e5834039bc17db7ebe3a4cec9492b
+charset-normalizer==2.0.9 \
+    --hash=sha256:1eecaa09422db5be9e29d7fc65664e6c33bd06f9ced7838578ba40d58bdf3721 \
+    --hash=sha256:b0b883e8e874edfdece9c28f314e3dd5badf067342e42fb162203335ae61aa2c
     # via requests
 click==8.0.3 \
     --hash=sha256:353f466495adaeb40b6b5f592f9f91cb22372351c84caeb068132442a4518ef3 \
@@ -84,27 +84,27 @@ commonmark==0.9.1 \
     --hash=sha256:452f9dc859be7f06631ddcb328b6919c67984aca654e5fefb3914d54691aed60 \
     --hash=sha256:da2f38c92590f83de410ba1a3cbceafbc74fee9def35f9251ba9a971d6d66fd9
     # via recommonmark
-cryptography==35.0.0 \
-    --hash=sha256:07bb7fbfb5de0980590ddfc7f13081520def06dc9ed214000ad4372fb4e3c7f6 \
-    --hash=sha256:18d90f4711bf63e2fb21e8c8e51ed8189438e6b35a6d996201ebd98a26abbbe6 \
-    --hash=sha256:1ed82abf16df40a60942a8c211251ae72858b25b7421ce2497c2eb7a1cee817c \
-    --hash=sha256:22a38e96118a4ce3b97509443feace1d1011d0571fae81fc3ad35f25ba3ea999 \
-    --hash=sha256:2d69645f535f4b2c722cfb07a8eab916265545b3475fdb34e0be2f4ee8b0b15e \
-    --hash=sha256:4a2d0e0acc20ede0f06ef7aa58546eee96d2592c00f450c9acb89c5879b61992 \
-    --hash=sha256:54b2605e5475944e2213258e0ab8696f4f357a31371e538ef21e8d61c843c28d \
-    --hash=sha256:7075b304cd567694dc692ffc9747f3e9cb393cc4aa4fb7b9f3abd6f5c4e43588 \
-    --hash=sha256:7b7ceeff114c31f285528ba8b390d3e9cfa2da17b56f11d366769a807f17cbaa \
-    --hash=sha256:7eba2cebca600a7806b893cb1d541a6e910afa87e97acf2021a22b32da1df52d \
-    --hash=sha256:928185a6d1ccdb816e883f56ebe92e975a262d31cc536429041921f8cb5a62fd \
-    --hash=sha256:9933f28f70d0517686bd7de36166dda42094eac49415459d9bdf5e7df3e0086d \
-    --hash=sha256:a688ebcd08250eab5bb5bca318cc05a8c66de5e4171a65ca51db6bd753ff8953 \
-    --hash=sha256:abb5a361d2585bb95012a19ed9b2c8f412c5d723a9836418fab7aaa0243e67d2 \
-    --hash=sha256:c10c797ac89c746e488d2ee92bd4abd593615694ee17b2500578b63cad6b93a8 \
-    --hash=sha256:ced40344e811d6abba00295ced98c01aecf0c2de39481792d87af4fa58b7b4d6 \
-    --hash=sha256:d57e0cdc1b44b6cdf8af1d01807db06886f10177469312fbde8f44ccbb284bc9 \
-    --hash=sha256:d99915d6ab265c22873f1b4d6ea5ef462ef797b4140be4c9d8b179915e0985c6 \
-    --hash=sha256:eb80e8a1f91e4b7ef8b33041591e6d89b2b8e122d787e87eeb2b08da71bb16ad \
-    --hash=sha256:ebeddd119f526bcf323a89f853afb12e225902a24d29b55fe18dd6fcb2838a76
+cryptography==36.0.1 \
+    --hash=sha256:0a817b961b46894c5ca8a66b599c745b9a3d9f822725221f0e0fe49dc043a3a3 \
+    --hash=sha256:2d87cdcb378d3cfed944dac30596da1968f88fb96d7fc34fdae30a99054b2e31 \
+    --hash=sha256:30ee1eb3ebe1644d1c3f183d115a8c04e4e603ed6ce8e394ed39eea4a98469ac \
+    --hash=sha256:391432971a66cfaf94b21c24ab465a4cc3e8bf4a939c1ca5c3e3a6e0abebdbcf \
+    --hash=sha256:39bdf8e70eee6b1c7b289ec6e5d84d49a6bfa11f8b8646b5b3dfe41219153316 \
+    --hash=sha256:4caa4b893d8fad33cf1964d3e51842cd78ba87401ab1d2e44556826df849a8ca \
+    --hash=sha256:53e5c1dc3d7a953de055d77bef2ff607ceef7a2aac0353b5d630ab67f7423638 \
+    --hash=sha256:596f3cd67e1b950bc372c33f1a28a0692080625592ea6392987dba7f09f17a94 \
+    --hash=sha256:5d59a9d55027a8b88fd9fd2826c4392bd487d74bf628bb9d39beecc62a644c12 \
+    --hash=sha256:6c0c021f35b421ebf5976abf2daacc47e235f8b6082d3396a2fe3ccd537ab173 \
+    --hash=sha256:73bc2d3f2444bcfeac67dd130ff2ea598ea5f20b40e36d19821b4df8c9c5037b \
+    --hash=sha256:74d6c7e80609c0f4c2434b97b80c7f8fdfaa072ca4baab7e239a15d6d70ed73a \
+    --hash=sha256:7be0eec337359c155df191d6ae00a5e8bbb63933883f4f5dffc439dac5348c3f \
+    --hash=sha256:94ae132f0e40fe48f310bba63f477f14a43116f05ddb69d6fa31e93f05848ae2 \
+    --hash=sha256:bb5829d027ff82aa872d76158919045a7c1e91fbf241aec32cb07956e9ebd3c9 \
+    --hash=sha256:ca238ceb7ba0bdf6ce88c1b74a87bffcee5afbfa1e41e173b1ceb095b39add46 \
+    --hash=sha256:ca28641954f767f9822c24e927ad894d45d5a1e501767599647259cbf030b903 \
+    --hash=sha256:e0344c14c9cb89e76eb6a060e67980c9e35b3f36691e15e1b7a9e58a0a6c6dc3 \
+    --hash=sha256:ebc15b1c22e55c4d5566e3ca4db8689470a0ca2babef8e3a9ee057a8b82ce4b1 \
+    --hash=sha256:ec63da4e7e4a5f924b90af42eddf20b698a70e58d86a72d943857c4c6045b3ee
     # via
     #   -r requirements.txt
     #   noiseprotocol
@@ -119,25 +119,29 @@ docutils==0.17.1 \
     #   recommonmark
     #   sphinx
     #   sphinx-rtd-theme
-graphviz==0.17 \
-    --hash=sha256:5dadec94046d82adaae6019311a30e0487536d9d5a60d85451f0ba32f9fc6559 \
-    --hash=sha256:ef6e2c5deb9cdcc0c7eece1d89625fd07b0f2208ea2bcb483520907ddf8b4e12
+graphviz==0.19.1 \
+    --hash=sha256:09ed0cde452d015fe77c4845a210eb642f28d245f5bc250d4b97808cb8f49078 \
+    --hash=sha256:f34088c08be2ec16279dfa9c3b4ff3d1453c5c67597a33e2819b000e18d4c546
     # via objgraph
 idna==3.3 \
     --hash=sha256:84d9dd047ffa80596e0f246e2eab0b391788b0503584e8945f2368256d2735ff \
     --hash=sha256:9d643ff0a55b762d5cdb124b8eaa99c66322e2157b69160bc32796e824360e6d
     # via requests
-imagesize==1.2.0 \
-    --hash=sha256:6965f19a6a2039c7d48bca7dba2473069ff854c36ae6f19d2cde309d998228a1 \
-    --hash=sha256:b1f6b5a4eab1f73479a50fb79fcf729514a900c341d8503d62a62dbc4127a2b1
+imagesize==1.3.0 \
+    --hash=sha256:1db2f82529e53c3e929e8926a1fa9235aa82d0bd0c580359c67ec31b2fddaa8c \
+    --hash=sha256:cd1750d452385ca327479d45b64d9c7729ecf0b3969a58148298c77092261f9d
     # via sphinx
-jinja2==3.0.2 \
-    --hash=sha256:827a0e32839ab1600d4eb1c4c33ec5a8edfbc5cb42dafa13b81f182f97784b45 \
-    --hash=sha256:8569982d3f0889eed11dd620c706d39b60c36d6d25843961f33f77fb6bc6b20c
+importlib-resources==5.4.0 \
+    --hash=sha256:33a95faed5fc19b4bc16b29a6eeae248a3fe69dd55d4d229d2b480e23eeaad45 \
+    --hash=sha256:d756e2f85dd4de2ba89be0b21dba2a3bbec2e871a42a3a16719258a11f87506b
+    # via jsonschema
+jinja2==3.0.3 \
+    --hash=sha256:077ce6014f7b40d03b47d1f1ca4b0fc8328a692bd284016f806ed0eaca390ad8 \
+    --hash=sha256:611bb273cd68f3b993fabdc4064fc858c5b47a973cb5aa7999ec1ba405c87cd7
     # via sphinx
-jsonschema==4.1.2 ; python_version >= "3.7" \
-    --hash=sha256:166870c8ab27bd712a8627e0598de4685bd8d199c4d7bd7cacc3d941ba0c6ca0 \
-    --hash=sha256:5c1a282ee6b74235057421fd0f766ac5f2972f77440927f6471c9e8493632fac
+jsonschema==4.3.2 ; python_version >= "3.7" \
+    --hash=sha256:8697a10a5a5edc922d2eb8556c7f35e814436f3ed8278ec2f65d40e9312d7c80 \
+    --hash=sha256:cca171fb7544de15ccda236bf78d58434d769c9a2ce21d44e0d209e39eeb8876
     # via -r requirements.txt
 lark-parser==0.6.7 \
     --hash=sha256:062800f3823a6c733ec1d181a2089a22d1f62dbe65f90a3f6b1e6de1934b05ef
@@ -221,9 +225,9 @@ objgraph==3.5.0 \
     --hash=sha256:4752ca5bcc0e0512e41b8cc4d2780ac2fd3b3eabd03b7e950a5594c06203dfc4 \
     --hash=sha256:deb821bc51a88ff103893aeeee2a8965eb0f719af2a363f49d63d894938b50b6
     # via -r requirements.txt
-packaging==21.2 \
-    --hash=sha256:096d689d78ca690e4cd8a89568ba06d07ca097e3306a4381635073ca91479966 \
-    --hash=sha256:14317396d1e8cdb122989b916fa2c7e9ca8e2be9e8060a6eff75b6b7b4d8a7e0
+packaging==21.3 \
+    --hash=sha256:dd47c42927d89ab911e606518907cc2d3a1f38bbd026385970643f9c5b8ecfeb \
+    --hash=sha256:ef103e05f519cdc783ae24ea4e2e0f508a9c99b2d4969652eed6a2e1ea5bd522
     # via
     #   deprecation
     #   sphinx
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
@@ -295,12 +299,13 @@ pygments==2.10.0 \
     --hash=sha256:b8e67fe6af78f492b3c4b3e2970c0624cbf08beb1e493b2c99b9fa1b67a20380 \
     --hash=sha256:f398865f7eb6874156579fdf36bc840a03cab64d1cde9e93d68f46a425ec52c6
     # via sphinx
-pympler==0.9 \
-    --hash=sha256:f2cbe7df622117af890249f2dea884eb702108a12d729d264b7c5983a6e06e47
+pympler==1.0 \
+    --hash=sha256:ca09ce58074a374a76328c27f0bb8a4e8d3964db1cbd1f9d3fd4c0d0746a9d16 \
+    --hash=sha256:f2e82c3e33835d0378ed95fffabc00806f4070f00decaa38b340ca99b1aca25c
     # via -r requirements.txt
-pyparsing==2.4.7 \
-    --hash=sha256:c203ec8783bf771a155b207279b9bccb8dea02d8f0c9e5f8ead507bc3246ecc1 \
-    --hash=sha256:ef9d7589ef3c200abe66653d3f1ab1033c3c419ae9b9bdb1240a85b024efc88b
+pyparsing==3.0.6 \
+    --hash=sha256:04ff808a5b90911829c55c4e26f75fa5ca8a2f5f36aa3a51f68e27033341d3e4 \
+    --hash=sha256:d9bdec0013ef1eb5a84ab39a3b3868911598afa494f5faa038647101504e2b81
     # via packaging
 pyrsistent==0.18.0 \
     --hash=sha256:097b96f129dd36a8c9e33594e7ebb151b1515eb52cceb08474c10a5479e799f2 \
@@ -379,13 +384,13 @@ six==1.16.0 \
     --hash=sha256:1e61c37477a1626458e36f7b1d82aa5c9b094fa4802892072e49de9c60c4c926 \
     --hash=sha256:8abb2f1d86890a2dfb989f9a77cfcfd3e47c2a354b01111771326f8aa26e0254
     # via -r requirements.txt
-snowballstemmer==2.1.0 \
-    --hash=sha256:b51b447bea85f9968c13b650126a888aabd4cb4463fca868ec596826325dedc2 \
-    --hash=sha256:e997baa4f2e9139951b6f4c631bad912dfd3c792467e2f03d7239464af90e914
+snowballstemmer==2.2.0 \
+    --hash=sha256:09b16deb8547d3412ad7b590689584cd0fe25ec8db3be37788be3810cbf19cb1 \
+    --hash=sha256:c8e1716e83cc398ae16824e5572ae04e0d9fc2c6b985fb0f900f5f0c96ecba1a
     # via sphinx
-sphinx==4.2.0 \
-    --hash=sha256:94078db9184491e15bce0a56d9186e0aec95f16ac20b12d00e06d4e36f1058a6 \
-    --hash=sha256:98a535c62a4fcfcc362528592f69b26f7caec587d32cd55688db580be0287ae0
+sphinx==4.3.2 \
+    --hash=sha256:0a8836751a68306b3fe97ecbe44db786f8479c3bf4b80e3a7f5c838657b4698c \
+    --hash=sha256:6a11ea5dd0bdb197f9c2abc2e0ce73e01340464feaece525e64036546d24c851
     # via
     #   -r requirements.txt
     #   recommonmark
@@ -419,17 +424,17 @@ sphinxcontrib-serializinghtml==1.1.5 \
     --hash=sha256:352a9a00ae864471d3a7ead8d7d79f5fc0b57e8b3f95e9867eb9eb28999b92fd \
     --hash=sha256:aa5f6de5dfdf809ef505c4895e51ef5c9eac17d0f287933eb49ec495280b6952
     # via sphinx
-sphinxcontrib-spelling==7.2.1 \
-    --hash=sha256:f09c1ddadf4f09ddbaef3ee210e6a18123c94fb5db5e11dfd5012208f73c35e0 \
-    --hash=sha256:f2578653014931b32c8c30d1a9930d998ae053b0d8b7adfbea0eb95a63e7a737
+sphinxcontrib-spelling==7.3.0 \
+    --hash=sha256:1af647e1d9fc7df0e08e327addbd69613bf751cb90aba0d531e69aee1e636133 \
+    --hash=sha256:a11799366f02fbd3390abf6aa2d4f0fe34df9be6e5ac0b1c8139dbd6c7fb0c99
     # via -r requirements.txt
 syslog-rfc5424-parser==0.3.2 \
     --hash=sha256:6134ee1958da89ab7f8d32ed5370a49ddabcc99d75a950b6ec59708417f20a7a \
     --hash=sha256:80a9239d4da404a271266000f4c5f00a183af3d03d53d19d7052c8272430bee9
     # via -r requirements.txt
-tomli==1.2.2 \
-    --hash=sha256:c6ce0015eb38820eaf32b5db832dbc26deb3dd427bd5f6556cf0acac2c214fee \
-    --hash=sha256:f04066f68f5554911363063a30b108d2b5a5b1a010aa8b6132af78489fe3aade
+tomli==2.0.0 \
+    --hash=sha256:b5bde28da1fed24b9bd1d4d2b8cba62300bfb4ec9a6187a957e8ddb9434c5224 \
+    --hash=sha256:c292c34f58502a1eb2bbb9f5bbc9a5ebc37bee10ffb8c2d6bbdfa8eb13cc14e1
     # via pep517
 urllib3==1.26.7 \
     --hash=sha256:4987c65554f7a2dbf30c18fd48778ef124af6fab771a377103da0585e2336ece \
@@ -439,6 +444,10 @@ wheel==0.37.0 \
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
  - Last done at Tue Dec 21 06:37:09 UTC 2021
