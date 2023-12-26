# voice-cloning

**Note**: Le notebook est à exécuter dans Google Colab. Vous avez besoin du dataset *data_cleaned.zip* que l'on importe dans le dossier /content/
Remplacer les fichiers du dossier /content/TTS-TT2/filelists/ par mes fichiers qui portent le même nom.

Les 

**Tree**:

[input](https://github.com/isabelleysseric/voice-cloning/tree/main/input)

  - filelists
      - list.txt
      - ljs_audio_text_test_filelists.txt
      - ljs_audio_text_train_filelists.txt
      - ljs_audio_text_val_filelists.txt
        
  - wavs
      - 1.npy
      - 1.wav
      - ...
      - 60.npy
      - 60.wav
   
output

  - audio
      - model_BS_6_0.00003_350epoch_0_original_audio.wav
      - model_BS_6_0.00003_350epoch_0_predicted_audio.wav
      - ...
      - model_BS_6_0.00003_350epoch_20_original_audio.wav
      - model_BS_6_0.00003_350epoch_20_predicted_audio.wav
      
      - model_BS_6_0.00003_350signals_epoch_0.png
      - ...
      - model_BS_6_0.00003_350signals_epoch_20.png
      
  - images
      - model_BS_6_0.00003_350_Alignment_Epoch_0_Iteration_9_Validation_Loss_1.7767614126205444.png
      - ...
      - model_BS_6_0.00003_350_Alignment_Epoch_20_Iteration_189_Validation_Loss_1.0240533351898193.png

  - logs
      - events.out.tfevents.1703405636.c8a2ca7defbc.1806.11
        
  - loss
      - model_BS_6_0.00003_350loss_curve_epoch_0.png
      - ...
      - model_BS_6_0.00003_350loss_curve_epoch_22.png
        
  - spectrogram
      - model_BS_6_0.00003_350spectrograms_epoch_0.png
      - ...
      - model_BS_6_0.00003_350spectrograms_epoch_20.png


MLSP Presentation_Clonage_de_la_voix.pdf
MLSP_Rapport_Clonage_de_la_voix.pdf
README.md
data_cleaned.zip
list.txt
ljs_audio_text_test_filelist.txt
ljs_audio_text_train_filelist.txt
ljs_audio_text_val_filelist.txt


  
