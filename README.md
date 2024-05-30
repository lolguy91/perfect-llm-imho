# The perfect LLM(Concept)
The idea to create the perfect LLM currently possible came to my mind because I was watching a YouTube on GaLore, the "sequel" to LoRa, and I realized how fucking groundbreaking that tech is. I was daydreaming about pretraining my own model, this (probably impossible to implement) concept is a refined version of that model.
## A rough sketch
it would have the following features:
- 1 or 2 billion parameters, lightweight for running on CPU
- Mixture Of Eperts architecture
- Support for 8 modalities/formats: text, image ,GIF ,binary blob ,PDF ,EPUB ,audio ,MIDI
- Trained on heavily filtered, yet unbiased and high quality data(only filtering out garbage like text from web apps)
- Uncensored(!!!)
- Quiet StAR support
- Beeg context window(at least 512k)
## Parameter count
Seeing that QWEN 1.5b runs perfectly on my PC, I can imagine some other model of comparable parameter count (maybe with a hint of quantization) can run well on a shitty laptop like my PC. We could get the performance of a larger model with Mixture of experts, which allows for "larger" models to run just a little, and Quiet StAR which gives the model a native inner monolouge.
## Mixture of experts
The basic idea is to have multiple sets of weights for the model, and switch them around according to the reccomendation of a switcher model, this allows for only a fraction of the parameters of the model to be used at one time. This means less computation for the poor CPU that has to run AI.
## Quiet StAR
IDK anything about this tech, but I think it adds an inner monolouge.
## Training
The idea is to put a ton of datasets together, deduplicate it, and filter out the bullshit. For images, we may use the trick of training an image summarising AI to create better captions for the image dataset. We also want to use self-made or self-collected data, because that is higher quality.
## No censorship or bias
The process is simple, add in some obedience dataset and some banned books, and it will be uncensored. As for bias, thats probably impossible to eliminate, but maybe we can control/limit it smh.
