  - Started at Wed Oct 13 06:34:36 UTC 2021
    - Running tweak 000-do-test-refresh-deps...
```
Found something to submit after 000-do-test-refresh-deps:
* ayourtch-000-do-test-refresh-deps
  master
diff --git a/test/requirements-3.txt b/test/requirements-3.txt
index 161f09d2c..f55fc0aa1 100644
--- a/test/requirements-3.txt
+++ b/test/requirements-3.txt
@@ -12,9 +12,9 @@ babel==2.9.1 \
     --hash=sha256:ab49e12b91d937cd11f0b67cb259a57ab4ad2b59ac7a3b41d6c06c0ac5b0def9 \
     --hash=sha256:bc0c176f9f6a994582230df350aa6e05ba2ebe4b3ac317eab29d9be5d2768da0
     # via sphinx
-certifi==2021.5.30 \
-    --hash=sha256:2bbf76fd432960138b3ef6dda3dde0544f27cbf8546c458e60baf371917ba9ee \
-    --hash=sha256:50b1e4f8446b06f41be7dd6338db18e0990601dce795c2b1686458aa7e8fa7d8
+certifi==2021.10.8 \
+    --hash=sha256:78884e7c1d4b00ce3cea67b44566851c4343c120abd683433ce934a68ea58872 \
+    --hash=sha256:d62a0163eb4c2344ac042ab2bdf75399a71a2d8c7d47eac2e2ee91b9d6339569
     # via requests
 cffi==1.14.6 \
     --hash=sha256:06c54a68935738d206570b20da5ef2b6b6d92b38ef3ec45c5422c0ebaf338d4d \
@@ -63,33 +63,39 @@ cffi==1.14.6 \
     --hash=sha256:f627688813d0a4140153ff532537fbe4afea5a3dffce1f9deb7f91f848a832b5 \
     --hash=sha256:fd4305f86f53dfd8cd3522269ed7fc34856a8ee3709a5e28b2836b2db9d4cd69
     # via cryptography
-charset-normalizer==2.0.4 \
-    --hash=sha256:0c8911edd15d19223366a194a513099a302055a962bca2cec0f54b8b63175d8b \
-    --hash=sha256:f23667ebe1084be45f6ae0538e4a5a865206544097e4e8bbcacf42cd02a348f3
+charset-normalizer==2.0.7 \
+    --hash=sha256:e019de665e2bcf9c2b64e2e5aa025fa991da8720daa3c1138cadd2fd1856aed0 \
+    --hash=sha256:f7af805c321bfa1ce6714c51f254e0d5bb5e5834039bc17db7ebe3a4cec9492b
     # via requests
-click==8.0.1 \
-    --hash=sha256:8c04c11192119b1ef78ea049e0a6f0463e4c48ef00a30160c704337586f3ad7a \
-    --hash=sha256:fba402a4a47334742d782209a7c79bc448911afe1149d07bdabdf480b3e2f4b6
+click==8.0.3 \
+    --hash=sha256:353f466495adaeb40b6b5f592f9f91cb22372351c84caeb068132442a4518ef3 \
+    --hash=sha256:410e932b050f5eed773c4cda94de75971c89cdb3155a72a0831139a79e5ecb5b
     # via pip-tools
 commonmark==0.9.1 \
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
+cryptography==35.0.0 \
+    --hash=sha256:07bb7fbfb5de0980590ddfc7f13081520def06dc9ed214000ad4372fb4e3c7f6 \
+    --hash=sha256:18d90f4711bf63e2fb21e8c8e51ed8189438e6b35a6d996201ebd98a26abbbe6 \
+    --hash=sha256:1ed82abf16df40a60942a8c211251ae72858b25b7421ce2497c2eb7a1cee817c \
+    --hash=sha256:22a38e96118a4ce3b97509443feace1d1011d0571fae81fc3ad35f25ba3ea999 \
+    --hash=sha256:2d69645f535f4b2c722cfb07a8eab916265545b3475fdb34e0be2f4ee8b0b15e \
+    --hash=sha256:4a2d0e0acc20ede0f06ef7aa58546eee96d2592c00f450c9acb89c5879b61992 \
+    --hash=sha256:54b2605e5475944e2213258e0ab8696f4f357a31371e538ef21e8d61c843c28d \
+    --hash=sha256:7075b304cd567694dc692ffc9747f3e9cb393cc4aa4fb7b9f3abd6f5c4e43588 \
+    --hash=sha256:7b7ceeff114c31f285528ba8b390d3e9cfa2da17b56f11d366769a807f17cbaa \
+    --hash=sha256:7eba2cebca600a7806b893cb1d541a6e910afa87e97acf2021a22b32da1df52d \
+    --hash=sha256:928185a6d1ccdb816e883f56ebe92e975a262d31cc536429041921f8cb5a62fd \
+    --hash=sha256:9933f28f70d0517686bd7de36166dda42094eac49415459d9bdf5e7df3e0086d \
+    --hash=sha256:a688ebcd08250eab5bb5bca318cc05a8c66de5e4171a65ca51db6bd753ff8953 \
+    --hash=sha256:abb5a361d2585bb95012a19ed9b2c8f412c5d723a9836418fab7aaa0243e67d2 \
+    --hash=sha256:c10c797ac89c746e488d2ee92bd4abd593615694ee17b2500578b63cad6b93a8 \
+    --hash=sha256:ced40344e811d6abba00295ced98c01aecf0c2de39481792d87af4fa58b7b4d6 \
+    --hash=sha256:d57e0cdc1b44b6cdf8af1d01807db06886f10177469312fbde8f44ccbb284bc9 \
+    --hash=sha256:d99915d6ab265c22873f1b4d6ea5ef462ef797b4140be4c9d8b179915e0985c6 \
+    --hash=sha256:eb80e8a1f91e4b7ef8b33041591e6d89b2b8e122d787e87eeb2b08da71bb16ad \
+    --hash=sha256:ebeddd119f526bcf323a89f853afb12e225902a24d29b55fe18dd6fcb2838a76
     # via
     #   -r requirements.txt
     #   noiseprotocol
@@ -97,9 +103,9 @@ deprecation==2.1.0 \
     --hash=sha256:72b3bde64e5d778694b0cf68178aed03d15e15477116add3fb773e581f9518ff \
     --hash=sha256:a10811591210e1fb0e768a8c25517cabeabcba6f0bf96564f8ff45189f90b14a
     # via -r requirements.txt
-docutils==0.16 \
-    --hash=sha256:0c5b78adfbf7762415433f5515cd5c9e762339e23369dbe8000d84a4bf4ab3af \
-    --hash=sha256:c2de3a60e9e7d07be26b7f2b00ca0309c207e06c100f9cc2a94931fc75a478fc
+docutils==0.17.1 \
+    --hash=sha256:686577d2e4c32380bb50cbb22f575ed742d58168cee37e99117a854bcd88f125 \
+    --hash=sha256:cf316c8370a737a022b72b56874f6602acf974a37a9fba42ec2876387549fc61
     # via
     #   recommonmark
     #   sphinx
@@ -108,17 +114,17 @@ graphviz==0.17 \
     --hash=sha256:5dadec94046d82adaae6019311a30e0487536d9d5a60d85451f0ba32f9fc6559 \
     --hash=sha256:ef6e2c5deb9cdcc0c7eece1d89625fd07b0f2208ea2bcb483520907ddf8b4e12
     # via objgraph
-idna==3.2 \
-    --hash=sha256:14475042e284991034cb48e06f6851428fb14c4dc953acd9be9a5e95c7b6dd7a \
-    --hash=sha256:467fbad99067910785144ce333826c71fb0e63a425657295239737f7ecd125f3
+idna==3.3 \
+    --hash=sha256:84d9dd047ffa80596e0f246e2eab0b391788b0503584e8945f2368256d2735ff \
+    --hash=sha256:9d643ff0a55b762d5cdb124b8eaa99c66322e2157b69160bc32796e824360e6d
     # via requests
 imagesize==1.2.0 \
     --hash=sha256:6965f19a6a2039c7d48bca7dba2473069ff854c36ae6f19d2cde309d998228a1 \
     --hash=sha256:b1f6b5a4eab1f73479a50fb79fcf729514a900c341d8503d62a62dbc4127a2b1
     # via sphinx
-jinja2==3.0.1 \
-    --hash=sha256:1f06f2da51e7b56b8f238affdd6b4e2c61e39598a378cc49345bc1bd42a978a4 \
-    --hash=sha256:703f484b47a6af502e743c9122595cc812b0271f661722403114f71a79d0f5a4
+jinja2==3.0.2 \
+    --hash=sha256:827a0e32839ab1600d4eb1c4c33ec5a8edfbc5cb42dafa13b81f182f97784b45 \
+    --hash=sha256:8569982d3f0889eed11dd620c706d39b60c36d6d25843961f33f77fb6bc6b20c
     # via sphinx
 lark-parser==0.6.7 \
     --hash=sha256:062800f3823a6c733ec1d181a2089a22d1f62dbe65f90a3f6b1e6de1934b05ef
@@ -243,23 +249,23 @@ ptyprocess==0.7.0 \
     --hash=sha256:4b41f3967fce3af57cc7e94b888626c18bf37a083e3651ca8feeb66d492fef35 \
     --hash=sha256:5c5d0a3b48ceee0b48485e0c26037c0acd7d29765ca3fbb5cb3831d347423220
     # via pexpect
-pycodestyle==2.7.0 \
-    --hash=sha256:514f76d918fcc0b55c6680472f0a37970994e07bbb80725808c17089be302068 \
-    --hash=sha256:c389c1d06bf7904078ca03399a4816f974a1d590090fecea0c63ec26ebaf1cef
+pycodestyle==2.8.0 \
+    --hash=sha256:720f8b39dde8b293825e7ff02c475f3077124006db4f440dcbc9a20b76548a20 \
+    --hash=sha256:eddd5847ef438ea1c7870ca7eb78a9d47ce0cdb4851a5523949f2601d0cbbe7f
     # via -r requirements.txt
 pycparser==2.20 \
     --hash=sha256:2d475327684562c3a96cc71adf7dc8c4f0565175cf86b6d7a404ff4c771f15f0 \
     --hash=sha256:7582ad22678f0fcd81102833f60ef8d0e57288b6b5fb00323d101be910e35705
     # via cffi
-pyenchant==3.2.1 \
-    --hash=sha256:37c79e1dab492092fe8135222b2ba404c1b79595b459af9edaeddb77a2cb89a5 \
-    --hash=sha256:49e0b255bef9356f57eeeee1d983ffa8599c0a46727d55cddbc71ec26226ca80 \
-    --hash=sha256:5e206a1d6596904a922496f6c9f7d0b964b243905f401f5f2f40ea4d1f74e2cf \
-    --hash=sha256:e8546c28b630f6d9f76642166656e337df2a1849cbef2b8ee198e7f64266f4ee
+pyenchant==3.2.2 \
+    --hash=sha256:1cf830c6614362a78aab78d50eaf7c6c93831369c52e1bb64ffae1df0341e637 \
+    --hash=sha256:5a636832987eaf26efe971968f4d1b78e81f62bca2bde0a9da210c7de43c3bce \
+    --hash=sha256:5facc821ece957208a81423af7d6ec7810dad29697cb0d77aae81e4e11c8e5a6 \
+    --hash=sha256:6153f521852e23a5add923dbacfbf4bebbb8d70c4e4bad609a8e0f9faeb915d1
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
@@ -268,9 +274,9 @@ pyparsing==2.4.7 \
     --hash=sha256:c203ec8783bf771a155b207279b9bccb8dea02d8f0c9e5f8ead507bc3246ecc1 \
     --hash=sha256:ef9d7589ef3c200abe66653d3f1ab1033c3c419ae9b9bdb1240a85b024efc88b
     # via packaging
-pytz==2021.1 \
-    --hash=sha256:83a4a90894bf38e243cf052c8b58f381bfe9a7a483f6a9cab140bc7f702ac4da \
-    --hash=sha256:eb10ce3e7736052ed3623d49975ce333bcd712c7bb19a58b9e2089d4057d0798
+pytz==2021.3 \
+    --hash=sha256:3672058bc3453457b622aab7a1c3bfd5ab0bdae451512f6cf25f64ed37f5b87c \
+    --hash=sha256:acad2d8b20a1af07d4e4c9d2e9285c5ed9104354062f275f3fcd88dcef4f1326
     # via babel
 recommonmark==0.7.1 \
     --hash=sha256:1b1db69af0231efce3fa21b94ff627ea33dee7079a01dd0a7f8482c3da148b3f \
@@ -291,17 +297,17 @@ snowballstemmer==2.1.0 \
     --hash=sha256:b51b447bea85f9968c13b650126a888aabd4cb4463fca868ec596826325dedc2 \
     --hash=sha256:e997baa4f2e9139951b6f4c631bad912dfd3c792467e2f03d7239464af90e914
     # via sphinx
-sphinx==4.1.2 \
-    --hash=sha256:3092d929cd807926d846018f2ace47ba2f3b671b309c7a89cd3306e80c826b13 \
-    --hash=sha256:46d52c6cee13fec44744b8c01ed692c18a640f6910a725cbb938bc36e8d64544
+sphinx==4.2.0 \
+    --hash=sha256:94078db9184491e15bce0a56d9186e0aec95f16ac20b12d00e06d4e36f1058a6 \
+    --hash=sha256:98a535c62a4fcfcc362528592f69b26f7caec587d32cd55688db580be0287ae0
     # via
     #   -r requirements.txt
     #   recommonmark
     #   sphinx-rtd-theme
     #   sphinxcontrib-spelling
-sphinx-rtd-theme==0.5.2 \
-    --hash=sha256:32bd3b5d13dc8186d7a42fc816a23d32e83a4827d7d9882948e7b837c232da5a \
-    --hash=sha256:4a05bdbe8b1446d77a01e20a23ebc6777c74f43237035e76be89699308987d6f
+sphinx-rtd-theme==1.0.0 \
+    --hash=sha256:4d35a56f4508cfee4c4fb604373ede6feae2a306731d533f409ef5c3496fdbd8 \
+    --hash=sha256:eec6d497e4c2195fa0e8b2016b337532b8a699a68bcb22a512870e16925c6a5c
     # via -r requirements.txt
 sphinxcontrib-applehelp==1.0.2 \
     --hash=sha256:806111e5e962be97c29ec4c1e7fe277bfd19e9652fb1a4392105b43e01af885a \
@@ -339,9 +345,9 @@ tomli==1.2.1 \
     --hash=sha256:8dd0e9524d6f386271a36b41dbf6c57d8e32fd96fd22b6584679dc569d20899f \
     --hash=sha256:a5b75cb6f3968abb47af1b40c1819dc519ea82bcc065776a866e8d74c5ca9442
     # via pep517
-urllib3==1.26.6 \
-    --hash=sha256:39fb8672126159acb139a7718dd10806104dec1e2f0f6c88aab05d17df10c8d4 \
-    --hash=sha256:f57b4c16c62fa2760b7e3d97c35b255512fb6b59a259730f36ba32ce9f8e342f
+urllib3==1.26.7 \
+    --hash=sha256:4987c65554f7a2dbf30c18fd48778ef124af6fab771a377103da0585e2336ece \
+    --hash=sha256:c4fdf4019605b6e5423637e01bc9fe4daef873709a7973e195ceba0a62bbc844
     # via requests
 wheel==0.37.0 \
     --hash=sha256:21014b2bd93c6d0034b6ba5d35e4eb284340e09d63c59aef6fc14b0f346146fd \
```
  - Last done at Wed Oct 13 06:35:05 UTC 2021
