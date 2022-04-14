# Kaggle

캐글데이터를 코랩에서 사용하는 방법

from kaggle_datasets import KaggleDatasets
GCS_DS_PATH = KaggleDatasets().get_gcs_path('bengaliai-cv19')
print(GCS_DS_PATH)

#이러한 코드를 사용하면 아래와 같이 gs:x의 형태로 나타나게 된다.
gs://kds-15f54468b501452666863b67d3322bb3a1cea340c3f0b0f8cb682edd
