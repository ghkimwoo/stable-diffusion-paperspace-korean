# stable-diffusion-paperspace-korean

_Paperspace를 위한 Jupyter notebook._

### 시작하기

**빠른 시작**
```bash
wget https://raw.githubusercontent.com/ghkimwoo/stable-diffusion-paperspace-korean/master/StableDiffusionUI_Voldemort_paperspace.ipynb
```

또는 노트북 파일을 다운로드하세요: [StableDiffusionUI_Voldemort_paperspace.ipynb](https://raw.githubusercontent.com/ghkimwoo/stable-diffusion-paperspace-korean/master/StableDiffusionUI_Voldemort_paperspace.ipynb)

이 노트북은 WebUI를 설정하는 거의 모든 과정을 자동화하도록 설계되었습니다.

가이드: [docs/Paperspace Guide for Idiots.md](https://github.com/ghkimwoo/stable-diffusion-paperspace-korean/blob/main/docs/Paperspace%20Guide%20for%20Idiots.md)

<br>

새 업데이트로 무언가를 망가뜨렸나요? 이 노트북의 이전 버전은 여기에서 다운로드하실 수 있습니다: https://github.com/ghkimwoo/stable-diffusion-paperspace-korean/commits/master
또는 https://github.com/Engineer-of-Stuff/stable-diffusion-paperspace/commits/master

<br>

### Python 3.10에 대한 참고 사항

Python 3.10은 WebUI를 실행하는 데 권장되는 Python 버전입니다. 문제가 발생하면 Python 3.10에서 WebUI를 실행하면 도움이 될까요? 페이퍼스페이스는 Python 3.9를 사용하므로 사용자 정의 컨테이너를 실행해야 합니다.

이미 머신을 생성한 경우 다음 지침에 따라 해당 머신을 삭제하고 새 머신을 생성하세요.: https://docs.paperspace.com/gradient/notebooks/runtimes/#how-to-specify-a-custom-container

다음 컨테이너 이미지를 사용해야 합니다.: `cyberes/gradient-base-py3.10:latest`


### xformers

여러 GPU용 휠을 컴파일했습니다. → https://github.com/Cyberes/xformers-compiled

### /other 폴더

다른 노트북과 이전 코드. (번역 되지 않음)

### /docs Directory
- [docs/Paperspace Guide for Idiots.md](https://github.com/Engineer-of-Stuff/stable-diffusion-paperspace/blob/main/docs/Paperspace%20Guide%20for%20Idiots.md): Paperspace에 노트북을 설치하는 방법을 알려드립니다.

### Linux

[stable-diffusion-webui-linux](https://github.com/Cyberes/stable-diffusion-webui-linux)를 참조하세요.
