# SeMAI-AI-WoodLog-Detection

Android setup:
* use "Interpreter" lib as build variant
* TF_OD_API_INPUT_SIZE = 320
* TF_OD_API_IS_QUANTIZED = false
* TF_OD_API_MODEL_FILE = "model_with_metadata.tflite"
* TF_OD_API_LABELS_FILE = "tflite_label_map.txt"
* MINIMUM_CONFIDENCE_TF_OD_API = 0.5f
* NUM_DETECTIONS = 100
