### Abstract

Fooling deep neural networks with adversarial input have exposed a significant vulnerability in the current state-of-the-art systems in multiple domains. Both black-box and white-box approaches have been used to either replicate the model itself or to craft examples which cause the model to fail. In this work, we propose a framework which uses multi-objective evolutionary optimization to perform both targeted and un-targeted black-box attacks on Automatic Speech Recognition (ASR) systems. 
We apply this framework on two ASR systems: Deepspeech and Kaldi-ASR, which increases the Word Error Rates (WER) of these systems by upto 980%, indicating the potency of our approach. During both un-targeted and targeted attacks, the adversarial samples maintain a high acoustic similarity of 0.98 and 0.97 with the original audio. 
 
Below are some of the adversarial samples generated on Kaldi-ASR and Deepspeech using the proposed framework in both targeted and untargeted setting. 

### Set-1  Un-targeted Attack
<table>
<tr>
<th><audio src="samples/ut_nsga_deepspeech_23_sample-000001.wav" controls preload></audio></th>
    <th><details>
        <summary style="color:red"> 
        Click to Reveal text
        </summary>
            <dl>
            <dt>Actual Text:  I have got to go him</dt>
            <dt>Genetated Text:  it got girl</dt>
            <dt>ASR: Deepspeech</dt>
            </dl>        
    </details></th>
</tr>
<tr>
<th><audio src="samples/ut_moga_deepspeech_29_sample-000001.wav" controls preload></audio></th>
    <th><details>
        <summary style="color:red">Click to Reveal text</summary>
        <dl>
        <dt>Actual Text:  I have got to go him</dt>
        <dt>Genetated Text: i get ill  </dt>
        <dt>ASR: Deepspeech</dt>
        </dl>
    </details> </th>
</tr>
<tr>
<th><audio src="samples/ut_nsga_kaldi_10_sample-000001.wav" controls preload></audio></th>
<th>
    <details>
    <summary style="color:red">Click to Reveal text</summary>
    <dl>
        <dt>Actual Text:  I have got to go him</dt>
        <dt>Genetated Text: the good girl to have  </dt>
        <dt>ASR: Kaldi-ASR</dt>
     </dl>   
    </details>
</th>
</tr>
<tr>
<th><audio src="samples/ut_moga_kaldi_15_sample-000001.wav" controls preload></audio>
</th>
<th>
    <details>
    <summary style="color:red">Click to Reveal text</summary>
    the scottish go to him  
    ASR:  Kaldi-ASR
    </details>  
</th>
</tr>
</table>

---
### Set-2  Un-targeted Attack

<table>
<tr>
        <th>
                <audio src="samples/ut_nsga_deepspeech_18_sample-000062.wav" controls preload></audio>
        </th>
        <th>
                <details>
                <summary style="color:red">Click to Reveal text</summary>
                <dl>
                <dt>Actual Text: he is the man that are written for </dt>
                <dt>Generated Text:  he is the man the tired   </dt>
                <dt> ASR: Deepspeech </dt>
                </dl>
                </details>
        </th>
</tr>
<tr>
        <th>
        <audio src="samples/ut_moga_deepspeech_18_sample-000062.wav" controls preload></audio>
        </th>
        <th>
            <details>
            <summary style="color:red">Click to Reveal text</summary>
            <dl>
                <dt>Actual Text: he is the man that are written for</dt>
                <dt>Generated Text:  hes the man their coverage   </dt>
                <dt> ASR: Deepspeech </dt>
                </dl>
            </details>  
        </th>
</tr>
<tr>    
        <th>
        <audio src="samples/ut_nsga_kaldi_9_sample-000062.wav" controls preload></audio>
        </th>
        <th>
            <details>
            <summary style="color:red"><em>Click to Reveal text</em></summary>
            <dl>
                <dt>Actual Text: he is the man that are written for</dt>
                <dt>Generated Text:  these the man that's all right    </dt>
                <dt> ASR: Kaldi-ASR </dt>
                </dl>
            </details>
        </th>
</tr>
<tr>
        <th>   
            <audio src="samples/ut_moga_kaldi_2_sample-000062.wav" controls preload></audio>
        </th>
        <th>
            <details>
            <summary style="color:red">Click to Reveal text</summary>
            <dl>
                <dt>Actual Text: he is the man that are written for</dt>
                <dt>Generated Text:    he's the man that are ready and four</dt>
                <dt> ASR: Kaldi-ASR </dt>
                </dl>
            </details>  
        </th>
</tr>
</table>

---
### Set-3 Un-targeted Attack

<table>
<tr>
    <th>
    <audio src="samples/ut_nsga_deepspeech_0_sample-000086.wav" controls preload></audio>
    </th>
    <th>
        <details>
        <summary style="color:red">Click to Reveal text</summary>
        <dl>
                <dt>Actual Text: this is for you</dt>
                <dt>Generated Text:           is it all   </dt>
                <dt> ASR: Deepspeech </dt>
                </dl>
        </details>
    </th>
</tr>
<tr>
    <th>    
    <audio src="samples/ut_moga_deepspeech_0_sample-000086.wav" controls preload></audio>
    </th>
    <th>
    <details>
    <summary style="color:red">Click to Reveal text</summary>
       <dl>
                <dt>Actual Text: this is for you</dt>
                <dt>Generated Text:  is it all   </dt>
                <dt> ASR: Deepspeech </dt>
        </dl>
    </details>  
    </th>
</tr>
<tr>
    <th>   
    <audio src="samples/ut_nsga_kaldi_0_sample-000086.wav" controls preload></audio>
    </th>
    <th>
            <details>
        <summary style="color:red">Click to Reveal text</summary>
        <dl>
                <dt>Actual Text: this is for you</dt>
                <dt>Generated Text: this is all you </dt>
                <dt> ASR: Kaldi-ASR </dt>
        </dl>
            </details>
    </th>
</tr>
<tr>
    <th> 
    <audio src="samples/ut_nsga_kaldi_0_sample-000086.wav" controls preload></audio>
    </th>
    <th>
        <details>
        <summary style="color:red">Click to Reveal text</summary>
        <dl>
                <dt>Actual Text: this is for you</dt>
                <dt>Generated Text: this is all you </dt>
                <dt> ASR: Kaldi-ASR</dt>
        </dl>
        </details>
    </th>        
</tr>
</table>

---

### Set-4 Targeted Attack

<table>
<tr>
    <th>
    <audio src="samples/tar_nsga_deepspeechsample-000001.wav" controls preload></audio>
    </th>
    <th>
        <details>
        <summary style="color:red">Click to Reveal text</summary>
        <dl>
                <dt>Actual Text: ive got to go to him</dt>
                <dt>Target Text: the caterpillar to have</dt>
                <dt>Generated Text: the caterpillar to have</dt>
                <dt>ASR: Deepspeech</dt>
        </dl>
        </details>
    </th>
 </tr>
 <tr>
    <th>   
    <audio src="samples/tar_moga_deepspeechsample-000001.wav" controls preload></audio>
    </th>
    <th>
    <details>
    <summary style="color:red">Click to Reveal text</summary>
      <dl>
                <dt>Actual Text: ive got to go to him</dt>
                <dt>Target Text: the caterpillar to have<</dt>
                <dt>Generated Text: the caterpillar to him</dt>
                <dt>ASR: Deepspeech</dt>
        </dl>
    </details>  
    </th>
  </tr>
<tr>
    <th>
    <audio src="samples/tar_nsga_kaldisample-000001.wav" controls preload></audio>
    </th>
    <th>
    <details>
    <summary style="color:red">Click to Reveal text</summary>
       <dl>
                <dt>Actual Text: ive got to go to him</dt>
                <dt>Target Text: the caterpillar to have</dt>
                <dt>Generated Text:  the caterpillar to have </dt>
                <dt>ASR: Kaldi-ASR</dt>
        </dl>
    </details>
    </th>
</tr>
<tr>
    <th>
    <audio src="samples/tar_moga_kaldisample-000001.wav" controls preload></audio>
    </th>
    <th>
        <details>
        <summary style="color:red">Click to Reveal text</summary>
        <dl>
                <dt>Actual Text: ive got to go to him</dt>
                <dt>Target Text:the caterpillar to have</dt>
                <dt>Generated Text:  the caterpillar to have </dt>
                <dt>ASR: Kaldi-ASR</dt>
        </dl>
        </details>  
    </th>
</tr>
</table>


---

### Set-5 Targeted Attack
<table>
<tr>
    <th>
    <audio src="samples/tar_nsga_deepspeechsample-000014.wav" controls preload></audio>
    </th>
    <th>
        <details>
        <summary style="color:red">Click to Reveal text</summary>
        <dl>
                <dt>Actual Text: follow the instructions here</dt>
                <dt>Target Text: all of these  </dt>
                <dt>Generated Text: all of these  </dt>
                <dt>ASR: Deepspeech</dt>
        </dl>
        </details>
    </th>
 </tr>
 <tr>
    <th>   
    <audio src="samples/tar_moga_deepspeechsample-000014.wav" controls preload></audio>
    </th>
    <th>
    <details>
    <summary style="color:red">Click to Reveal text</summary>
     <dl>
                <dt>Actual Text: follow the instructions here</dt>
                <dt>Target Text: all of these  </dt>
                <dt>Generated Text: all of these  </dt>
                <dt>ASR: Deepspeech</dt>
        </dl>
    </details>  
    </th>
  </tr>
<tr>
    <th>
    <audio src="samples/tar_nsga_kaldisample-000014.wav" controls preload></audio>
    </th>
    <th>
    <details>
    <summary style="color:red">Click to Reveal text</summary>
       <dl>
                <dt>Actual Text: follow the instructions here</dt>
                <dt>Target Text: all of these  </dt>
                <dt>Generated Text: all the institutions here </dt>
                <dt>ASR: Kaldi-ASR</dt>
        </dl>
    </details>
    </th>
</tr>
<tr>
    <th>
    <audio src="samples/tar_moga_kaldisample-000014.wav" controls preload></audio>
    </th>
    <th>
        <details>
        <summary style="color:red">Click to Reveal text</summary>
           <dl>
                <dt>Actual Text: follow the instructions here</dt>
                <dt>Target Text: all of these  </dt>
                <dt>Generated Text: all these russians year </dt>
                <dt>ASR: Kaldi-ASR</dt>
        </dl>
        </details>  
    </th>
</tr>
</table>

---

### Set-6 Targeted Attack
<table>
 <tr>
    <th>   
    <audio src="samples/tar_moga_deepspeechsample-000047.wav" controls preload></audio>
    </th>
    <th>
    <details>
    <summary style="color:red">Click to Reveal text</summary>
     <dl>
                <dt>Actual Text: never mind about that</dt>
                <dt>Target Text: they will mind   </dt>
                <dt>Generated Text: they will mind   </dt>
                <dt>ASR: Deepspeech</dt>
        </dl>
    </details>  
    </th>
  </tr>
<tr>
    <th>
    <audio src="samples/tar_nsga_deepspeechsample-000047.wav" controls preload></audio>
    </th>
    <th>
        <details>
        <summary style="color:red">Click to Reveal text</summary>
        <dl>
                <dt>Actual Text: never mind about that</dt>
                <dt>Target Text: they will mind   </dt>
                <dt>Generated Text: they were minodat   </dt>
                <dt>ASR: Deepspeech</dt>
        </dl>
        </details>
    </th>
 </tr>
<tr>
    <th>
    <audio src="samples/tar_nsga_kaldisample-000047.wav" controls preload></audio>
    </th>
    <th>
    <details>
    <summary style="color:red">Click to Reveal text</summary>
       <dl>
                <dt>Actual Text: never mind about that</dt>
                <dt>Target Text: they will mind   </dt>
                <dt>Generated Text:they reminded us that    </dt>
                <dt>ASR: Kaldi-ASR</dt>
        </dl>
    </details>
    </th>
</tr>
<tr>
    <th>
    <audio src="samples/tar_moga_kaldisample-000047.wav" controls preload></audio>
    </th>
    <th>
        <details>
        <summary style="color:red">Click to Reveal text</summary>
           <dl>
                 <dt>Actual Text: never mind about that</dt>
                <dt>Target Text: they will mind   </dt>
                <dt>Generated Text: how her mind a out that </dt>
                <dt>ASR: Kaldi-ASR</dt>
        </dl>
        </details>  
    </th>
</tr>
</table>

---
