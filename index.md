### Abstract

Fooling deep neural networks with adversarial input have exposed a significant vulnerability in the current state-of-the-art systems in multiple domains. Both black-box and white-box approaches have been used to either replicate the model itself or to craft examples which cause the model to fail. In this work, we propose a framework which uses multi-objective evolutionary optimization to perform both targeted and un-targeted black-box attacks on Automatic Speech Recognition (ASR) systems. 
We apply this framework on two ASR systems: Deepspeech and Kaldi-ASR, which increases the Word Error Rates (WER) of these systems by upto 980%, indicating the potency of our approach. During both un-targeted and targeted attacks, the adversarial samples maintain a high acoustic similarity of 0.98 and 0.97 with the original audio. 

More details are available in the Paper. Few of the adversarial samples generated on Kaldi-ASR and Deepspeech are below:

### Set-1
<audio src="samples/ut_nsga_deepspeech_23_sample-000001.wav" controls preload></audio><details>
<summary>Click to Reveal text</summary>
it got girl  
ASR: Deepspeech
</details>
<audio src="samples/ut_moga_deepspeech_29_sample-000001.wav" controls preload></audio><details>
<summary>Click to Reveal text</summary>
i get ill  
ASR: Deepspeech
</details>  
>
<audio src="samples/ut_nsga_kaldi_10_sample-000001.wav" controls preload></audio><details>
<summary>Click to Reveal text</summary>
the good girl to have  
ASR: Kaldi-ASR
</details>
<audio src="samples/ut_moga_kaldi_15_sample-000001.wav" controls preload></audio><details>
<summary>Click to Reveal text</summary>
the scottish go to him  
ASR:  Kaldi-ASR
</details>  
>

--- 
### Set-2

<audio src="samples/ut_nsga_deepspeech_0_sample-000086.wav" controls preload></audio><details>
<summary>Click to Reveal text</summary>
is it all   
#### ASR: Deepspeech
</details>
<audio src="samples/ut_moga_deepspeech_0_sample-000086.wav" controls preload></audio><details>
<summary>Click to Reveal text</summary>
is it all  
ASR: Deepspeech
</details>  
>
<audio src="samples/ut_nsga_kaldi_0_sample-000086.wav" controls preload></audio><details>
<summary>Click to Reveal text</summary>
this is all you  
ASR: Kaldi-ASR
</details>
<audio src="samples/ut_nsga_kaldi_0_sample-000086.wav" controls preload></audio><details>
<summary>Click to Reveal text</summary>
this is all you  
ASR:  Kaldi-ASR
</details>  
>

---

### Set-3

<audio src="samples/ut_nsga_deepspeech_18_sample-000062.wav" controls preload></audio><details>
<summary>Click to Reveal text</summary>
he is the man the tired   
#### ASR: Deepspeech
</details>
<audio src="samples/ut_moga_deepspeech_18_sample-000062.wav" controls preload></audio><details>
<summary>Click to Reveal text</summary>
hes the man their coverage
ASR: Deepspeech
</details>  
>
<audio src="samples/ut_nsga_kaldi_9_sample-000062.wav" controls preload></audio><details>
<summary><em>blue</em>Click to Reveal text</summary>
these the man that's all right 
ASR: Kaldi-ASR
</details>
<audio src="samples/uut_moga_kaldi_2_sample-000062.wav" controls preload></audio><details>
<summary>Click to Reveal text</summary>
he's the man that are ready and four
ASR:  Kaldi-ASR
</details>  
>
