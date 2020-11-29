# StreamCNNTesting
Set of jupyter notebook files used for the analysis presented at a talk at the 2020 Fast Machine Learning for Science Conference.

## Setup Instructions
*Feel free to switch python versions or not use a virtualenv at all.* <br>
*This will also require vivado hls to be added to your path.*
```
git clone https://github.com/veyron8800/StreamCNNTesting.git && \
cd StreamCNNTesting && \
python3.8 -m virtualenv venv && \
source venv/bin/activate && \
pip install -r requirements.txt && \
git clone --branch cnn_stream https://github.com/veyron8800/hls4ml.git && \
cd hls4ml && \
pip install . && \
cd .. && \
git clone https://github.com/google/qkeras && \
cd qkeras && \
pip install . && \
cd .. && \
jupyter notebook
```
