# How to download

`magnet:?xt=urn:btih:5bde442da86265b670a3e5ea3163afad2c6f8ecc&dn=novelaileak&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2F9.rarbg.com%3A2810%2Fannounce&tr=udp%3A%2F%2Ftracker.openbittorrent.com%3A6969%2Fannounce&tr=http%3A%2F%2Ftracker.openbittorrent.com%3A80%2Fannounce&tr=udp%3A%2F%2Fopentracker.i2p.rocks%3A6969%2Fannounce`

The above link is leaked Novel AI models,consisting of NLP models and painting models. Verifying sha256 is strongly recommended. If you just want to use NovelAI to paint, you just need `random_stableckpt` folder which content model checkpoints.  

You should better use `animefull-final-pruned` or `animefull-latest` whose result is best. 

Usually, you use NovelAI with stable-diffusion WebUI. To do that, please copy checkpoint file (.ckpt file) to `.../stable-diffusion-webui/models/Stable-diffusion` and rename `model.ckpt` as the name which it should be.(to enable you to distinguish them.) After doing that, you can move original checkpoint file to anywhere you like. 

# The things you should do and should not do

## What you should do

Open `http://127.0.0.1:7860/` , click `settings` tab, and change these settings.

+ change `Stop At last layers of CLIP model` as `2`
+ change `Eta noise seed delta` as `31337`

You **NEED NOT** use hyper network, because official version doesn't use it.

If possible, you should use Semi-precision. Never mind if it will blur image, differences are extremely barely visible.  

