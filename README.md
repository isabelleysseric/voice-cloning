<h1 align="center"> Voice Cloning</h1>
<br/>
<br/>

<p align="center">
  <img src="https://github.com/isabelleysseric/voice-cloning/blob/main/output/test_model_image.png" />
</p>  

<h2 align="center">    

  <!-- GitHub -->
  <a href="https://github.com/isabelleysseric/">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" >
  </a>  

  <!-- Project Repo -->
  <a href="https://github.com/isabelleysseric/Voice-Cloning/">
    <img src="https://img.shields.io/badge/Repo-Voice_Cloning-green?style=for-the-badge&logo={Voice-Cloning}&logoColor=white" >
  </a>

  <!-- Wiki Project -->
  <a href="https://github.com/isabelleysseric/Voice-Cloning/wiki/">
    <img src="https://img.shields.io/badge/Wiki-Voice_Cloning-green?style=for-the-badge&logo={Voice-Cloning}&logoColor=white" >
  </a><br> 
  
</h2>
<br/>

**Note**: The `Voice_cloning_Training_with_Tacotron2_and_WaveGlow.ipynb` notebook is to be run in *Google Colab*. Once in Colab, you need to import the *data_cleaned.zip* dataset into the current folder `/content/`.
Replace the files in the folder `/content/TTS-TT2/filelists/` with my files that have the same name after installing Tacotron2. LThe rest of the code will take care of unzipping it and putting it in the new folder `/content/TTS-TT2/wavs/`.
The program will then ask you to load your transcription file. You will give it the `list.txt` file.

The files in the `input` folder are needed to give input to the speech synthesis model. They are also found at the root of the project. The wav files correspond to the zip file: `data_cleaned.zip` and the `list.txt`, `ljs_audio_text_val_filelists.txt`, `ljs_audio_text_val_filelists.txt` and `ljs_audio_text_val_filelists.txt`files are also found at the root of the project.
The files in the `output` folder are the results of the model, during and after training.

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

