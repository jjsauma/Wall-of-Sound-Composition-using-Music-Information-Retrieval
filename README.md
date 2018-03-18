# wos1
Using MIR to help create a Wall of Sound Composition

Wall of Sound is a production and sound design technique based on layering sounds to create a fuller and thicker sound. You can find a deeper explanation of this technique here https://en.wikipedia.org/wiki/Wall_of_Sound
I am creating a wall of sound with a collection of audio samples that I selected because I think that will sound good together. An extensive collection of samples was analyzed previously, and for this exercise, I choose the ones that are in the same tonality.
When layering sounds I have observed that there is a tendency of accumulating energy around 1kHz and 2Kh, and this creates an uncomfortable sound. This notebook proposes a method to help the sound designer decide how to avoid this accumulation of energy either by eliminating some sounds or distribute them across the spectrum to have the same energy across the whole spectrum and create a pleasant sound.
To distribute this sounds, I have found that the Spectral Centroid calculation helps in finding the sound's position in the spectrum.
This notebook helps to analyze a set of audio files, find their Spectral Centroid, and to classify them by setting each sound into one of three categories: low, mid, high.
Joaquin Jimenez Sauma (SMC17)
