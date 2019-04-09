### Abstract

Fooling deep neural networks with adversarial input have exposed a significant vulnerability in the current state-of-the-art systems in multiple domains. Both black-box and white-box approaches have been used to either replicate the model itself or to craft examples which cause the model to fail. In this work, we propose a framework which uses multi-objective evolutionary optimization to perform both targeted and un-targeted black-box attacks on Automatic Speech Recognition (ASR) systems. 
We apply this framework on two ASR systems: Deepspeech and Kaldi-ASR, which increases the Word Error Rates (WER) of these systems by upto 980\%, indicating the potency of our approach. During both un-targeted and targeted attacks, the adversarial samples maintain a high acoustic similarity of 0.98 and 0.97 with the original audio. 

More details are available in the Paper. Few of the adversarial samples generated on Kaldi-ASR and Deepspeech are below:


 <audio src="samples/sample-000001.wav" controls preload></audio><details>
    <summary>Click to Reveal text</summary>
    I have got to got to him 
    </details>
<audio src="samples/ut_nsga_deepspeech_23_sample-000001.wav" controls preload></audio>
<details>
<summary>Click to Reveal text</summary>
it got girl  
</details>
<audio src="samples/ut_moga_deepspeech_29_sample-000001.wav" controls preload></audio>
<details>
<summary>Click to Reveal text</summary>
i get ill  
</details>  
>


<audio src="samples/tar_moga_deepspeechsample-000001.wav" controls preload></audio>
<details>
<summary>Click to Reveal text</summary>
a cat 
</details>
<audio src="samples/tar_moga_kaldisample-000001.wav" controls preload></audio>
<details>
<summary>Click to Reveal text</summary>
```
a cat 
```
</details>
You can use the [editor on GitHub](https://github.com/ShreyaKhare/audio-adversairial/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown
<audio src="samples/tar_moga_deepspeechsample-000001.wav" controls preload></audio>
<details>
<summary>Click to toggle contents of `code`</summary>
```
CODE!
```
</details>

<details>
<summary>Click to toggle contents of other `code`</summary>
```
MORE CODE!
```
</details>
Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for



# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/ShreyaKhare/audio-adversairial/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
