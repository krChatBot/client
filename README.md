# 음잘알(music recommendation chatbot service)

챗봇 기반 음악 추천 서비스인 "**음잘알**"은 Azure 웹 앱 서비스와 QnAMaker를 이용하였고, python 크롤링을 이용하여 자료를 수집하였습니다.

## version
> version: 0.1  
>> 사용자 입력에 echo로 반응  
>> 아이템 설계  

> version: 0.3  
>> https://www.youtube.com/watch?v=enS81adc9Rg  
>> QnAMaker를 활용하여 동적 챗봇 구성  
>> 음악 추천 아이템을 챗봇에 구현  

> version: 0.5  
>> https://www.youtube.com/watch?v=A2nRczLdrGA&t=20s  
>> Crawling을 이용한 음악 추천 기능 구안  

> version: 1.0
>> 
>> 감정과 대화를 다양하게 추가, 음악을 추가하여 더 포괄적인 입력에 대응하도록 변경

# Information
**Term**: 2020.07.04 - 2020.07.25
**URL (Githup-page)**:  
**Contributors**:
<center>
|![sh](./contributor/sh.jpg)|![hs](./contributor/hs.jpg)|
|---|----|
| SEOCKHUN BAE | HYUCKSOON JANG |
</center>

## Start with Bot Framework

챗봇을 Local에서 실행해보세요!

**Windows**: git-bash
**Linux**: shell(git)

` git clone https://github.com/krChatBot/client `

로 모든 파일을 다운받고 해당 파일을 **릴리즈**로 실행

- Bot Framework Emulator 실행
- `http://localhost:3978/api/messages` URL로 접속

## Azure Web App

[Azure]([https://azure.microsoft.com/ko-kr/](https://azure.microsoft.com/ko-kr/))에서는 웹 프레임워크 뿐만 아니라 다양한 Web App 그리고 바로 사용할 수 있는 Web App bot 까지 지원합니다. 

## QnAMaker

[QnAMaker]([https://www.qnamaker.ai/](https://www.qnamaker.ai/))를 이용하여 정적 대화를 더 포괄적으로 받아들일 수 있도록 학습하였습니다. 

## Docs

- [Bot Framework Documentation](https://docs.botframework.com)
- [Bot Basics](https://docs.microsoft.com/azure/bot-service/bot-builder-basics?view=azure-bot-service-4.0)
- [Dialogs](https://docs.microsoft.com/azure/bot-service/bot-builder-concept-dialog?view=azure-bot-service-4.0)
- [Gathering Input Using Prompts](https://docs.microsoft.com/azure/bot-service/bot-builder-prompts?view=azure-bot-service-4.0&tabs=csharp)
- [Activity processing](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-concept-activity-processing?view=azure-bot-service-4.0)
- [Azure Bot Service Introduction](https://docs.microsoft.com/azure/bot-service/bot-service-overview-introduction?view=azure-bot-service-4.0)
- [Azure Bot Service Documentation](https://docs.microsoft.com/azure/bot-service/?view=azure-bot-service-4.0)
- [Azure CLI](https://docs.microsoft.com/cli/azure/?view=azure-cli-latest)
- [Azure Portal](https://portal.azure.com)
- [Channels and Bot Connector Service](https://docs.microsoft.com/azure/bot-service/bot-concepts?view=azure-bot-service-4.0)