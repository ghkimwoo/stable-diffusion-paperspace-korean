# `Getting Started on Paperspace for Retards <3`

![paperspace](https://raw.githubusercontent.com/Engineer-of-Stuff/stable-diffusion-paperspace/main/docs/assets/paperspace.png)

**Paperspace가 무엇인가요?**

기본적으로 독점 모델을 개발하는 전문가를 대상으로 하는 AI 개발용 클라우드 컴퓨팅 서비스입니다. 하드웨어에서 코드를 실행합니다. 신경망 개발에 사용할 수 있는 정말 멋진 기능들을 많이 제공하지만, 저희는 Gradient만 사용하고 있습니다.

**왜 Paperspace 인가요?**

Paperspace는 편리하며, AI를 실행하기에 충분한 컴퓨터가 없을 수도 있습니다. 전문가를 대상으로 하는 반면 Colab은 말 그대로 어린이를 위한 서비스입니다.
2023.09.01 현황 : 현재 무료 요금제에서 GPU를 사용할 수 있는 할당량이 모두 차서 사용할 수 없으며, *8$의 Pro 이상에서만* GPU를 사용할 수 있습니다.

강력한 GPU에서 코드를 실행하면 컴퓨터 로컬보다 훨씬 빠르고 쉽게 코드를 실행할 수 있습니다.



**비용을 지불해야 하나요?**

현재 기준으로 지불해야합니다. 정말 깔끔한 이미지를 생성하는 데 필요한 모든 것을 갖추고 있어야 합니다. Paperspace가 Google Colab Pro보다 저렴하다고 확신합니다.

월 기준 (2023.09.01 기준 설명)
Paperspace Pro : 8$
Google Colab Pro : 9.99$

Paperspace Growth : 39$
Google Colab Pro+ : 49.99$

자세한 결제 정보는 [Paperspace Plans](https://www.paperspace.com/pricing)과 [Colab Plans](https://colab.research.google.com/signup)를 참조하세요.

**왜 Google Colab이 아닌가요?**

Google Colab도 대안이 될 수 있지만 사용자가 생성하는 모든 내용을 기록할 가능성이 높습니다.

Google은 컴퓨터가 꺼지면 파일을 삭제합니다. Paperspace는 무료 티어에서도 그렇게 하지 않습니다.


## 해봅시다!



1. [계정_생성](https://console.paperspace.com/signup) 휴대폰 번호를 입력하라는 메시지가 표시됩니다.

2. 이 버튼을 클릭하고 팝업되는 양식을 작성합니다.

3. 업그레이드를 선택하여 프로 이상의 요금제를 선택해야합니다.

![프로젝트_만들기](https://raw.githubusercontent.com/ghkimwoo/stable-diffusion-paperspace-korean/main/docs/assets/create_project.png)

3. 노트북을 만들려면 이 버튼을 클릭하세요.

![노트북_만들기](https://raw.githubusercontent.com/ghkimwoo/stable-diffusion-paperspace-korean/main/docs/assets/create_notebook.png)

4. "런타임"에서 "처음부터 시작"을 선택합니다.

![시작_스크래치.png](https://raw.githubusercontent.com/ghkimwoo/stable-diffusion-paperspace-korean/main/docs/assets/start_scratch.png)

5. 다운로드 [StableDiffusionUI_Voldemort_paperspace.ipynb](https://github.com/ghkimwoo/stable-diffusion-paperspace-korean/blob/main/StableDiffusionUI_Voldemort_paperspace.ipynb)
오른쪽 상단에 있는 'Raw' 버튼을 클릭하고 Raw 텍스트가 있는 페이지에서 `ctrl+s`를 실행하세요. 웹페이지를 다운로드하지 마세요.

노트북에서 터미널을 열고 이 명령을 실행해 노트북을 컴퓨터로 다운로드할 수도 있습니다. 그런 다음 6단계를 건너뜁니다.

```
wget https://raw.githubusercontent.com/ghkimwoo/stable-diffusion-paperspace-korean/master/StableDiffusionUI_Voldemort_paperspace.ipynb
```

6. 해당 파일을 노트북에 업로드하세요

전체 리포지토리를 복제/다운로드할 필요 없이 '.ipynb' 파일만 복제/다운로드하면 됩니다.

![upload](https://raw.githubusercontent.com/Engineer-of-Stuff/stable-diffusion-paperspace/main/docs/assets/upload.png)

7. 지시 사항 따르기

설정 프로세스를 자동화하고 실수가 없도록 하기 위해 열심히 노력했습니다. 읽어보세요!

![final](https://raw.githubusercontent.com/Engineer-of-Stuff/stable-diffusion-paperspace/main/docs/assets/final.png)
(이 이미지는 오래되었습니다.)

## Jupyter 노트북 실행

왼쪽 세로 메뉴 표시줄에서 이 기호를 클릭합니다.

![open-jupiter](https://raw.githubusercontent.com/Engineer-of-Stuff/stable-diffusion-paperspace/main/docs/assets/open-jupiter.png)

주피터 노트북에서 터미널에 액세스할 수 있습니다.

## Python 3.10에 대한 참고 사항

Python 3.10은 WebUI를 실행하는 데 권장되는 Python 버전입니다. 문제가 발생하면 Python 3.10에서 WebUI를 실행하면 도움이 될까요? Paperspace는 Python 3.9를 사용하므로 사용자 정의 컨테이너를 실행해야 합니다.

이미 머신을 생성한 경우 다음 지침에 따라 해당 머신을 삭제하고 새 머신을 생성하세요.: https://docs.paperspace.com/gradient/notebooks/runtimes/#how-to-specify-a-custom-container

다음 컨테이너 이미지를 사용해야 합니다.: `cyberes/gradient-base-py3.10:latest`

## 도움이 더 필요합니다 :(

다음은 다른 가이드입니다. 기술 지원 질문으로 /sdg/를 엉망으로 만들지 마세요.

다음은 다른 가이드 중 하나에 도움이 될 만한 내용입니다:
- [A guide to getting started with the paperspace port of AUTOMATIC1111’s web UI for ppl who get nervous](https://proximacentaurib.notion.site/A-guide-to-getting-started-with-the-paperspace-port-of-AUTOMATIC1111-s-web-UI-for-ppl-who-get-nervou-b83c2213f17e452e8b0e37ba64fe9758)
- [Getting Started Stable Diffusion 2 in Paperspace Notebook](https://weirdwonderfulai.art/resources/getting-started-stable-diffusion-2-in-paperspace-notebook/)
- [How to Setup Deforum Stable Diffusion WebUI on Paperspace (video)](https://www.youtube.com/watch?v=YuislijDeFo)

## WebUI 관련 기타 가이드

- [FINAL GUI RETARD GUIDE](https://rentry.org/voldy)
- [Using the WebUI](https://rentry.org/voldy)
- [Using the Inpainter](https://rentry.org/drfar)
- [Textual Inversion](https://rentry.org/aikgx)
- [Crowd-Sourced Prompts](https://lexica.art/)
- [Artist Name Prompts](https://sgreens.notion.site/sgreens/4ca6f4e229e24da6845b6d49e6b08ae7?v=fdf861d1c65d456e98904fe3f3670bd3)

![](https://mato.evulid.cc/matomo.php?idsite=2&rec=1&url=https://rentry.org/865dy)

[Images hosted on Github](https://github.com/Engineer-of-Stuff/stable-diffusion-paperspace)
[Github Mirror](https://github.com/Engineer-of-Stuff/stable-diffusion-paperspace/blob/main/docs/archives/Getting%20Started%20on%20Paperspace.pdf)

[Approved by Paperspace!](https://github.com/Engineer-of-Stuff/stable-diffusion-paperspace/blob/master/docs/assets/approved%20by%20paperspace.png?raw=true)
