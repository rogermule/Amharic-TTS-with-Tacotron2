# Amharic Text to speech with Tacotron2 

This repo is text to speech implemented on **Tacotron2** paper [Natural TTS Synthesis By Conditioning Wavenet On Mel Spectrogram Predictions](https://arxiv.org/pdf/1712.05884.pdf)

Basic Model implementation is adobted from [NVIDIA'S tacotron2 implemetation](https://github.com/NVIDIA/tacotron2) and [NVIDIA'S waveglow implementation] (https://github.com/NVIDIA/waveglow). it is implemented by pytorch and it is only supported with GPU. 

I am inspired by Tacotron implementation by [Keith Ito](https://github.com/keithito/tacotron).

## audio samples generated by the model (Tacotron2 + waveglow)

* ጤና ይስጥልኝ እኔ በባህር ዳር ዩኒቨርሲቲ የ 5ኛ ዓመት የሶፍትዌር ምህንድስና ተማሪወች የተሰራሁ የአማረኛ ጽሁፍን ወደ ድምፅ የሚቀይር ነኝ ። [link](https://github.com/EdenMelaku/Amharic-TTS-with-Tacotron2/blob/master/Generated%20Audio%20samples/103_synthesis.wav)

t’ēna yisit’ilinyi inē bebahiri dari yunīverisītī ye 5nya ‘ameti yesofitiwēri mihinidisina temarīwechi yeteserahu ye’āmarenya ts’ihufini wede dimit͟s’i yemīk’eyiri nenyi ።


* ድምፄን ያገኘሁት ከህሊና ብዙነህ ነው ፤ በተጨማሪም ኤልሻዳይ ፣ ህይወት እና ኤደን በስራው ላይ ተሳትፈዋል ። [link](https://github.com/EdenMelaku/Amharic-TTS-with-Tacotron2/blob/master/Generated%20Audio%20samples/104_synthesis.wav)

dimit͟s’ēni yagenyehuti kehilīna bizunehi newi ፤ betech’emarīmi ēlishadayi ፣ hiyiweti ina ēdeni besirawi layi tesatifewali


* በዚያን ወቅት  በ 1977 ዓ.ም ማለት ነው የተከሰተውን የከፋ ረሃብ ተከትሎ የድጋፍ እጆች የተዘረጉት ከመላው ዓለም ነበር ። [link](https://github.com/EdenMelaku/Amharic-TTS-with-Tacotron2/blob/master/Generated%20Audio%20samples/2_synthesis_last.wav)

bezīyani wek’iti  be 1977 ‘a.mi maleti newi yetekesetewini yekefa rehabi teketilo yedigafi ijochi yetezereguti kemelawi ‘alemi neberi ።


* ነፍሰጡር ሴቶች በተለይም በእርግዝናቸው የመጨረሻ ወራት ለፀረ አረም ኬሚካሎችና ማዳበሪያዎች በስፋት የሚጋለጡ ከሆነ ፣ በሆዳቸው በያዙት ፅንስ ላይ ከፍተኛ የጤና ችግር የመፍጠራቸው ዕድል ሰፊ ከመሆኑም በላይ ልጃቸውን ያለቀኑ ለመውለድ ይገደዳሉ ብሏል ዘገባው ። [link](https://github.com/EdenMelaku/Amharic-TTS-with-Tacotron2/blob/master/Generated%20Audio%20samples/10_synthesis_last.wav)

nefiset’uri sētochi beteleyimi be’irigizinachewi yemech’eresha werati let͟s’ere āremi kēmīkalochina madaberīyawochi besifati yemīgalet’u kehone ፣ behodachewi beyazuti t͟s’inisi layi kefitenya yet’ēna chigiri yemefit’erachewi ‘idili sefī kemehonumi belayi lijachewini yalek’enu lemewiledi yigededalu bilwali zegebawi ።




## Audio samples generated by Waveglow model (trained on 44K sample rate audio samples)





