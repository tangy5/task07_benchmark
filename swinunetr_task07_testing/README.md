

# Evaluation

To evaluate a `Swin UNETR` on a single GPU, place the model checkpoint in `pretrained_models` folder and
provide its name using `--pretrained_model_name`:

JSON file already included. 

Traianed checkpoints: 

SwinUNETR: <a href="https://drive.google.com/file/d/1SWzpUPe1gbmCZgdLr28T3FZCCkExhpEZ/view?usp=sharing"> link</a>.

```bash
python test.py --json_list=<json-path> --data_dir=<data-path> --feature_size=<feature-size>\
--infer_overlap=0.5 --pretrained_model_name=<model-name>
```
