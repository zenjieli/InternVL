DS_BUILD_FUSED_ADAM=1 pip install deepspeed --upgrade

KeyError: 'architectures'
Downgrading to transformers==4.44.2 solved this issue for me.

Merge LORA:
you can simply copy the merge_lora.py from intern_chat/tools to the intern_chat/ folder, which is the same folder with internvl module.

Tutorial:
<https://internvl.readthedocs.io/en/latest/tutorials/coco_caption_finetune.html>