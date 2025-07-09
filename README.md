# ai-workflows

각종 AI툴들 활용에 사용되는 workflow 들을 정리.
주로 comfyUI 와 dify 가 메인이 될 예정입니다.

## All in one make AI pic v1
* 스케치 등의 이미지를 받아서 controlet canny 혹은 depth 를 적용해 이미지를 생성하거나,
* 혹은 이미지를 받아서 이미지를 생성하는 용도로 사용하는 워크플로입니다.
* 보조적으로 프롬프트를 주면 이미지를 생성해 줍니다.
* 자세한 내용은 [https://gcempire.tistory.com/700](https://gcempire.tistory.com/700) 를 참고해 주세요.
* 관련된 데이터는 아래와 같습니다.
	* comfyUI workflow
	  ![comfyui/comfyui_any-image-to-ai_v1.png](comfyui/comfyui_any-image-to-ai_v1.png)
	* dify workflow :
	  [dify/all_in_one_make_ai_pic_v1.yml](dify/all_in_one_make_ai_pic_v1.yml)