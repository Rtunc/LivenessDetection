# LivenessDetection



Dataset: gồm 2 thư mục Live % Spoof ứng với label true & false

face_detector: model face detection

Model: trained liveness detection (tải từ link kaggle-output :https://www.kaggle.com/code/anhnguynthch/livenessdetect/output) 

Gather_example : cắt vid thành các ảnh chứa khuôn mặt đặt vào file dataset

liveness_demo:

Run:

	python liveness_demo.py --model Model --detector face_detector
	
	
