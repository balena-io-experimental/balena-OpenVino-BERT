# balena-OpenVino-BERT

![alt text](https://static.wikia.nocookie.net/muppet/images/e/e1/Bert_smile.png/revision/latest/scale-to-width-down/280?cb=20110630173259)

The original application and usage instructions are located here:  [https://github.com/openvinotoolkit/open_model_zoo/blob/master/demos/bert_question_answering_demo/python/README.md](https://github.com/openvinotoolkit/open_model_zoo/blob/master/demos/bert_question_answering_demo/python/README.md)

Open up a terminal via balenaCloud, and try to run this command:

```
python3 /opt/intel/openvino_2021.3.394/deployment_tools/open_model_zoo/demos/bert_question_answering_demo/python/bert_question_answering_demo.py --vocab=/opt/intel/openvino_2021.3.394/deployment_tools/open_model_zoo/models/intel/bert-small-uncased-whole-word-masking-squad-0001/vocab.txt --model=/opt/intel/openvino_2021.3.394/deployment_tools/open_model_zoo/demos/models/intel/bert-small-uncased-whole-word-masking-squad-0001/FP32/bert-small-uncased-whole-word-masking-squad-0001.xml --input_names="input_ids,attention_mask,token_type_ids" --output_names="output_s,output_e" --input="https://en.wikipedia.org/wiki/Bert_(Sesame_Street)" -c
```
