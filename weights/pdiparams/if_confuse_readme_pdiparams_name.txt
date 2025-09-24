205_final_output_best_acc_infer: LP text Detection
205_rec_final_infer: text recognition (chinese and english version, just in case sth go wrong, else use the english version)
281_3_dein_rec_en_train2infer: text recognition (English only version)
PP-OCRv3_mobile_det_white_to_color_best18_infer: Using PPOCR-v3 instead of v4 and v5, LP text Detection (trained on white color plate first, then transition to color plates)
ppv3_w_rec: Using PPOCR-v3 rec instead of v4 or v5, LP text recognition (trained on white color plate only, work for all colors)

# Some notes:
IDK through my exps, v4 or v5 det and rec perform kinda worst than this v3.
Some testing have been done on v5 rec (det just outright refuse to detect even a blurry line) before, it does perform ok on like super blurry plate, but worst in general. 
-h1: because of data train?
-h2: diff backbones?
-h3: diff hyperparams?
-h4: diff the way trained? I don't remember how I process through things anymore.
