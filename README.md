# LivenessDetection



Dataset: gồm 2 thư mục Live % Spoof ứng với label true & false

face_detector: model face detection

CNN_model: trained liveness detection (tải từ link kaggle-output :https://www.kaggle.com/code/anhnguynthch/livenessdetect/output) 

Gather_example : cắt vid thành các ảnh chứa khuôn mặt đặt vào file dataset

liveness_demo:

Run:

	python liveness_demo.py --model CNN_model --detector face_detector
	
	
