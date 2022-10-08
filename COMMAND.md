
```bash
python tools/infer/predict_rec.py \
    --image_dir="./doc/imgs_words/en/word_1.png" \
    --rec_model_dir="en_PP-OCRv3_det_infer" \
    --rec_char_dict_path="ppocr/utils/en_dict.txt"
```

```bash
python3 tools/infer/predict_rec.py \
    --image_dir="./doc/imgs_words/korean/1.jpg" \
    --rec_model_dir="./korean_mobile_v2.0_rec_infer" \
    --rec_char_dict_path="ppocr/utils/dict/korean_dict.txt" \
    --vis_font_path="doc/fonts/korean.ttf"
```

```bash
python tools/infer/predict_system.py \
    --image_dir="./doc/myDemo/023.png" \
    --det_model_dir="./en_PP-OCRv3_det_infer" \
    --rec_model_dir="./en_PP-OCRv3_rec_infer" \
    --rec_char_dict_path="ppocr/utils/en_dict.txt" \
    --use_angle_cls=false
```