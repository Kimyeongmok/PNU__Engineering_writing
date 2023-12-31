# ChatGPT의 성능은 정말 저하되었는가?
전기컴퓨터공학부 201924436 김영목

이 글은 최근 많은 관심을 받고 있는 ChatGPT의 성능과 관련된 한 기사의 내용에 의문을 가져 쓰게 되었다. 해당 글인 <<’멍청해진' 챗GPT....성능 저하의 이유는?>>에 대해 얘기해보면 이 글은 Standford 연구진의 ChatGPT의 2023년 3월, 그리고 당해 6월의 성능을 비교한 연구 내용을 근거로 ChatGPT의 성능이 과거에 비해 저하되었다는 식의 내용을 소개한다. 그러나 해당 Standford 연구진의 연구 내용과 결과를 보니 정말 이 기사가 강조하는 대로 ChatGPT의 성능이 저하된 것인가에 대해서 의문이 생겼다.

이 글의 사실관계에 대해 의문이 생긴 것은 크게 2가지였다. 첫번째는 정말 이 기사에서 소개한 연구 글의 ChatGPT 성능 저하에 대한 분석 기준이 신뢰할 만 한가? 이다. 분석 표 밑에 달린 연구 글을 인용해보면 “결과는 GPT-4가 정답의 2%를 조금 넘는 정확도의 감소를 나타냄을 나타냅니다. 이 특정 테스트는 본질적인 수학적 능력을 보여주는 것이 아니라 데이터를 회상하는 모델의 능력을 주로 평가한다는 점에 유의하는 것이 중요합니다. 이 작업은 특히 소수와 관련하여 모델에 계산 유효성 검사 및 추론 기능이 없기 때문에 메모리 리콜을 중심으로 진행됩니다.
ChatGPT XNUMX월까지 성능 지표에서 상당한 성장을 보여 XNUMX배 이상의 놀라운 개선을 보여주었습니다. 이 연구가 이러한 향상에 기여하는 특정 요인을 조사하지는 않았지만, ChatGPT수학적 추론 및 문제 해결 능력의 발전.”[2]
인용 글을 잘 보면, 즉 실험에서 정확도가 떨어진 이유는 ChatGPT가 소수를 판별하는 부분에서 성능이 떨어졌다는 것이 아니라 ChatGPT에 유효성 검사 및 추론 기능이 없다는 부분을 주목하여 소수에 관해 반복된 질문을 계속 함으로써 메모리 리콜을 중심으로 답변하는 ChatGPT가 갈수록 똑같은 질문에 한정된 메모리의 내용으로만 답변으로 하니 자연스럽게 정확도가 떨어지는 답변을 할 수밖에 없었다는 뜻이 된다. 인용 글의 두 번째 문단을 보면 결과적으로는 오히려 성능면에선 정확한 조사는 하지 못했지만 발전이 이뤄졌을 수 있음을 암시하고 있다.

두번째는 정말 해당 Stanford 연구진의 연구 글이 ChatGPT의 성능 저하에 대해 긍정하는 글이었는가? 하는 점이다. 해당 연구 내용 중 결론 파트를 인용해보면 “결과적으로 결과나 실험 자체가 모델 열화의 증거로 간주될 수 없음이 명백해집니다. 대신, 모델은 응답을 생성하는 다른 접근 방식을 보여 주며 잠재적으로 교육의 변형을 반영합니다.” [2]라고 한다. 연구 글은 나름의 기준으로 기사 내용처럼 ChatGPT의 성능 저하에 대해 연구한 내용을 소개하곤 있지만 결과적으로 ChatGPT의 성능 저하를 뚜렷하게 증명해냈지 못했음을 밝히고 있다. 애초에 이 기사에서 인용했던 연구 글의 내용은 ChatGPT의 성능 저하에 대해 긍정하는 글이 아니었던 것이다.

그렇다면 어째서 기사에선 연구 글의 결과와 정반대되는 내용을 소개했을까? 그것에 대해서만은 당사자가 아닌 이상 그 내막을 완전히 알 순 없다. 그러나 어찌됐든 이러한 자극적인 제목과 내용의 글들은 상대적으로 사람들에게 읽히기 쉽고 그만큼 더 잘못된 정보가 무분별하게 돌아다니는 사태를 야기하게 된다. 따라서 이러한 부분은 상당히 아쉬운 부분이라고 생각한다. 앞으로 연구 글을 더 정확히 읽으며 이러한 부분들에 더 신경을 쓴다면 더 좋은 글이 될 수 있으리라 생각한다.
	



참고문헌

[1]<<’멍청해진' 챗GPT....성능 저하의 이유는?>>, URL:
https://www.thedailypost.kr/news/articleView.html?idxno=100903


[2] <<Stanford의 연구는 GPT-4가 멍청해지고 있음을 확인합니다.>>, URL:
https://mpost.io/ko/%EC%8A%A4%ED%83%A0%ED%8F%AC%EB%93%9C-%EC%97%B0%EA%B5%AC-%D1%81gpt-4%EA%B0%80-%EB%8D%94-%EB%A9%8D%EC%B2%AD%ED%95%B4%EC%A7%80%EA%B3%A0-%EC%9E%88%EC%9D%8C%EC%9D%84-%ED%99%95%EC%9D%B8/