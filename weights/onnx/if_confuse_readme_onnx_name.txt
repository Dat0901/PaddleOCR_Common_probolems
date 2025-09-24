# Use for onnx inference

205_final_output_best_acc.onnx : Text detection for car license plates
205_rec_final.onnx : Text recognition for car license plates (use dict ppocr_keys_v1.txt, this is general version, with rec both chinese and english. This for fallback, else for normal, use english version named below.)
281_3_dein_rec_en_train2infer.onnx : Text recognition for car license plate (use dict en_dict.txt)
PP-OCRv3_mobile_det_white_to_color_best18.onnx: Text detection for car lps (trained on white lps, then trained on color lps. idk but it yeild better result than straight color or mix)
ppv3_w_rec.onnx: Text recoginition for car lps (use en_dict.txt, trained for en white text only (can work on colors plate), mostly because there are no chinese plate in Vietnam).
