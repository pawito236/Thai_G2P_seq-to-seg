# Thai_G2P_seq-to-seg [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1qmJMbBn0Yp0-Sakej3ADDdWZKVmINCfY?usp=sharing)

 Using cmusphinx / g2p-seq2seq
 
 G2P คือการแปลงขอความจากตัวเขียน เช่น “ฉัน รัก เธอ” → สัทอักษร (Phoneme) หรือ อักษรที่ใช้กำหนดแทนเสียงนั่นเอง ตัวอย่างรูปที่ขึ้้นปกนั้น คือ output ที่ได้จากการ Train Thai G2P ครั้งนี้นั่นเอง หากทุกคนทำตามบทความนี้ ทุกคนจะสามารถเปลี่ยนคำใด ๆ ในภาษาไทยให้เป็น Phoneme ได้แน่นอน (แต่ต้องมี Data ให้โมเดล Train สักหน่อยนะ)
 
 โดย Tool ที่จะนำเสนอให้ลองใช้นั้นคือ [cmusphinx](https://github.com/cmusphinx/g2p-seq2seq) เพราะมี pipeline การเตรียม Data and Training ที่ง่าย ๆ มาก ๆ
 
 
## Demo [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1pHSM8ZsYHsbXKvd0lE4RWI-61iFV8cR7?usp=sharing)
[Demo TTS Tacotron2 with G2P model](https://medium.com/@pawito236/demo-tts-tacotron2-with-g2p-model-e4006fc831ba) การสังเคราะห์เสียงภาษาไทยด้วย Tacotron 2 ร่วมกับ G2P model

## References and Related repos
[cmusphinx](https://github.com/cmusphinx/g2p-seq2seq) The tool does Grapheme-to-Phoneme (G2P) conversion using transformer model from tensor2tensor toolkit

[G2P Sequence-to-Sequence](https://medium.com/nectec/g2p-sequence-to-sequence-53a843d6702a) ใช้ Sequence-to-Sequence G2P toolkit ของ [cmusphinx](https://github.com/cmusphinx/g2p-seq2seq)



## license
NECTEC licensed TSync2 under CC-BY-NC-SA

## Medium
[Thai G2P seq-to-seq](https://medium.com/@pawito236/thai-g2p-seq-to-seq-a1eb96c3be18)

![chan rak ther2](https://user-images.githubusercontent.com/44425803/163362514-3c7e242e-cc41-4628-8fd2-a5e1a6a1ec7e.jpg)

