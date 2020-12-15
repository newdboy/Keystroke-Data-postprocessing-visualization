## Keystroke-Data-postprocessing-visualization
Kologger(https://github.com/isingmodel/Kologger)의 자잘한 버그 수정을 위한 data postprocessor와 visualizer입니다.

# postprocessor
pyqt와 pynput데이터를 종합하여 데이터를 refine하는 기존의 refine_data 모듈에 이하의 모듈을 추가하여 실행하면 됩니다.
자세한 내용은 postprocessor & pausetime graph(201215).ipynb 파일을 참고하세요.

(confirmation bias 사례 연구에 활용했던 것을 그대로 가져온 것임)



# visualizer
ipywidgets 패키지의 slider형태의 interactive widget을 사용하여 시간대 별로 작성한 full text를 검토하는 visualizer를 만들었습니다.
자세한 내용은 sliding visualizer.ipynb 파일을 참고하세요.
