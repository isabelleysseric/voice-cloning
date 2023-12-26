# Voice Cloning
<br/>
<br/>

<p align="center">
  <img src="https://github.com/isabelleysseric/voice-cloning/blob/main/output/test_model_image.png" />
</p>  

<p align='center'>
  <a href="https://github.com/isabelleysseric/voice-cloning/tree/main">voice-cloning</a> (GitHub)
  &nbsp; • &nbsp;<a href="https://github.com/isabelleysseric/voice-cloning/wiki">voice-cloning</a> (Wiki)<br/>
  <a href="https://github.com/isabelleysseric">isabelleysseric</a> (GitHub)
  &nbsp; • &nbsp;<a href="https://isabelleysseric.com/">isabelleysseric.com</a> (Portfolio)
  &nbsp; • &nbsp;<a href="https://www.linkedin.com/in/isabelle-eysseric/">isabelle-eysseric</a> (LinkedIn) <br/>
</p>
<br/>
<br/>

**Note**: Le notebook `Voice_cloning_Training_with_Tacotron2_and_WaveGlow.ipynb` est à exécuter dans *Google Colab*. Une fois dans Colab, vous avez besoin d'importer le dataset *data_cleaned.zip* dans le dossier courant `/content/`
Remplacer les fichiers du dossier `/content/TTS-TT2/filelists/` par mes fichiers qui portent le même nom apres avoir installé Tacontron2. Le reste du code s'occupera de le décompresser et de le mettre dans le nouveau dossier `/content/TTS-TT2/wavs/`
Le programme vous demandera ensuite de charger votre fichier de transcription. Vous lui donnerez le fichier `list.txt`  

Les fichiers dans le dossier `input` sont necessaires pour donner en entrée au modele de synthese vocale. On les retrouve aussi à la racine du projet. Les fichiers wavs correspoindent au fichier zip: data_cleaned.zip et les fichiers `list.txt`, `ljs_audio_text_val_filelists.txt`, `ljs_audio_text_val_filelists.txt` et `ljs_audio_text_val_filelists.txt` se retrouvent également à la racine du projet.  
Les fichiers dans le dossier `output` sont les résultats du modele, pendant et apres l'apprentissage.  

**TREE**:

[input](https://github.com/isabelleysseric/voice-cloning/tree/main/input)

  - [filelists](https://github.com/isabelleysseric/voice-cloning/tree/main/input/wavs)
      - `list.txt`
      - `ljs_audio_text_test_filelists.txt`
      - `ljs_audio_text_train_filelists.txt`
      - `ljs_audio_text_val_filelists.txt`
        
  - [wavs](https://github.com/isabelleysseric/voice-cloning/tree/main/input/audio)
      - `1.npy`
      - `1.wav`
      - ...
      - `60.npy`
      - `60.wav`
   
[output](https://github.com/isabelleysseric/voice-cloning/tree/main/output)

  - [audio](https://github.com/isabelleysseric/voice-cloning/tree/main/output/audio)
      - `model_BS_6_0.00003_350epoch_0_original_audio.wav`
      - `model_BS_6_0.00003_350epoch_0_predicted_audio.wav`
      - ...
      - `model_BS_6_0.00003_350epoch_20_original_audio.wav`
      - `model_BS_6_0.00003_350epoch_20_predicted_audio.wav`
      
      - `model_BS_6_0.00003_350signals_epoch_0.png`
      - ...
      - `model_BS_6_0.00003_350signals_epoch_20.png`
      
  - [images](https://github.com/isabelleysseric/voice-cloning/tree/main/output/images)
      - `model_BS_6_0.00003_350_Alignment_Epoch_0_Iteration_9_Validation_Loss_1.7767614126205444.png`
      - ...
      - `model_BS_6_0.00003_350_Alignment_Epoch_20_Iteration_189_Validation_Loss_1.0240533351898193.png`

  - [logs](https://github.com/isabelleysseric/voice-cloning/tree/main/output/logs)
      - `events.out.tfevents.1703405636.c8a2ca7defbc.1806.11`
        
  - [loss](https://github.com/isabelleysseric/voice-cloning/tree/main/output/loss)
      - `model_BS_6_0.00003_350loss_curve_epoch_0.png`
      - ...
      - `model_BS_6_0.00003_350loss_curve_epoch_22.png`
        
  - [spectrogram](https://github.com/isabelleysseric/voice-cloning/tree/main/output/spectrogram)
      - `model_BS_6_0.00003_350spectrograms_epoch_0.png`
      - ...
      - `model_BS_6_0.00003_350spectrograms_epoch_20.png`


[Voice_cloning_Training_with_Tacotron2_and_WaveGlow.ipynb](https://github.com/isabelleysseric/voice-cloning/blob/main/Voice_cloning_Training_with_Tacotron2_and_WaveGlow.ipynb)  
[MLSP Presentation_Clonage_de_la_voix.pdf](https://github.com/isabelleysseric/voice-cloning/blob/main/MLSP%20Presentation_Clonage_de_la_voix.pdf)  
[MLSP_Rapport_Clonage_de_la_voix.pdf](https://github.com/isabelleysseric/voice-cloning/blob/main/MLSP_Rapport_Clonage_de_la_voix.pdf)  
[README.md](https://github.com/isabelleysseric/voice-cloning/blob/main/README.md)  
[data_cleaned.zip](https://github.com/isabelleysseric/voice-cloning/blob/main/data_cleaned.zip)  
[list.txt](https://github.com/isabelleysseric/voice-cloning/blob/main/list.txt)  
[ljs_audio_text_test_filelist.txt](https://github.com/isabelleysseric/voice-cloning/blob/main/ljs_audio_text_test_filelist.txt)  
[ljs_audio_text_train_filelist.txt](https://github.com/isabelleysseric/voice-cloning/blob/main/ljs_audio_text_train_filelist.txt)  
[ljs_audio_text_val_filelist.txt](https://github.com/isabelleysseric/voice-cloning/blob/main/ljs_audio_text_val_filelist.txt)  


<br/>
<br/>
<p align='center'>
  <a href="https://github.com/isabelleysseric/voice-cloning/tree/main">Voice-Cloning</a> (GitHub)
  &nbsp; • &nbsp;<a href="https://github.com/isabelleysseric/voice-cloning/wiki">Voice-Cloning</a> (Wiki)<br/>
  <a href="https://github.com/isabelleysseric">isabelleysseric</a> (GitHub)
  &nbsp; • &nbsp;<a href="https://isabelleysseric.com/">isabelleysseric.com</a> (Portfolio)
  &nbsp; • &nbsp;<a href="https://www.linkedin.com/in/isabelle-eysseric/">isabelle-eysseric</a> (LinkedIn) <br/>
</p>
<br/>
<br/>
