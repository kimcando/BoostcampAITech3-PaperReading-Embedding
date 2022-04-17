# Boostcamp AI Tech 3rd : Basic Paper Reading w.r.t Embedding
### TL;DR
```
1992년부터 2018년도까지 이루어진 word/sentence embedding의 중요한 줄기를 이루는 기초 논문 스터디를 진행하고자 합니다. 
```

<br/>

### 논문 정리 발표에 들어갈 내용
* 저자가 풀려고 하는 문제는 어떤 것인가?
* 어떤 식으로 해결하고자 했는가. 어떤 장점이 있는가(시간 여유가 된다면, 이전에는 어떤 방법이 있었고 그 방법들의 단점)
* 그 방법에 대한 intuition (수학 없이)
* 방법에 대한 이해(수학적으로)
* 방법의 성공성을 보여주기 위해 사용한 데이터, 메트릭, 성능비교
* 부족하다 생각되는 것, 애매한 것, 혹은 좋았던 점 등의 Discussion point

<br/>

### 리딩 리스트

| Dates | Paper(author)                                                                                     | Year | Presenter | File upload | Code explained |
|-------|---------------------------------------------------------------------------------------------------|------|-----------|-------------|----------------|
|       | Class-Based n-gram Models of Natural Language(Peter F Brown, et al.)                              | 1992 |   소연   |    [설명](https://docs.google.com/presentation/d/1BFrCpcl7GxT3iiqGXajjYAZbsEAjUslhtbkBlQau8AE/edit?usp=sharing)         |           |   
|       | Efficient Estimation of Word Representations in Vector Space(Tomas Mikolov, et al)                | 2013 |    동진       |    [발표](https://github.com/kimcando/BoostcampAITech3-PaperReading-Embedding/files/8284506/default.pptx)         |                |
|       | Distributed Representations of Words and Phrases and their Compositionality(Tomas Mikolov, et al) | 2013 |   나연   |   [설명](https://wry-silence-4ef.notion.site/Distributed-Representations-of-Words-and-Phrases-and-their-Compositionality-95186fac1ee641359589c2a92267ef29)  |   [skip-gram](https://github.com/kimcando/BoostcampAITech3-PaperReading-Embedding/tree/main/materials/skip-gram), [CBOW](https://github.com/kimcando/BoostcampAITech3-PaperReading-Embedding/tree/main/materials/cbow)          |
|       | Distributed Representations of Sentences and Documents(Quoc V. Le and Tomas Mikolov)               | 2014 |   기원   |  [설명](https://catnip-pelican-5b8.notion.site/DOC2VEC-72913173f6484646a7873add95e24195)           | [Doc2Vec](https://github.com/cbowdon/doc2vec-pytorch)               |  
|       | GloVe: Global Vectors for Word Representation(Jeffrey Pennington, et al.)                         | 2015 |           |             |                |
|       | Skip-Thought Vectors(Ryan Kiros, et al.)                                                          | 2015 |           |             |                |
|       | Enriching Word Vectors with Subword Information(Piotr Bojanowski, et al.)                         | 2017 |           |             |                |
|       | Universal Sentence Encoder(Daniel Cer et al.)                                                     | 2018 |           |             |                |

<br/>

### issue & 추가 스터디 자료

| Dates | Topic              | Presenter | File upload  |
|-------|--------------------|-----------|-------------|
|04/14  | genism을 이용한 word2vec 사용 | 현지 |[링크](https://drive.google.com/file/d/1EMRV7neUNTV1A2r3lOWcbHdAf21-5olz/view?usp=sharing)|
|04/14  | negative samping & subsampling | 나경 | [링크](https://angiekang.tistory.com/31)|
|04/14  | hierarchical softmax | 소연 | [링크](https://github.com/kimcando/BoostcampAITech3-PaperReading-Embedding/blob/main/materials/hierarchical_softmax.pdf)|
|04/14  | negative contrastive estimation(NCE) | 수정| [링크](https://drive.google.com/file/d/1JZv107HqzXtO3klmqE_-IkMsdFG9J1Pc/view?usp=sharing) |

### 스터디 룰
* 스터디 시간 : 목요일 저녁 9시 30분! 
* 스터디 분량 : 매주 1주씩! (프로덕트 서빙 커리큘럼 기간에 집중할 수 있게 그전에 끝내보아영)
    * 각각 읽고, 질문 최소 1개를 github issue에 올림(+ 거기에 대한 답변을 안다면 답변 달아주기!)
* 발표자 : 해당 요일에 랜덤 선택. 발표 자료는 자유 양식
    * 논문 발표 : 발표자는 발표 후 정리 내용 해당 레포 폴더파서 업로드. 발표자 외 사람 중 공유하고 싶은 사람은 issues에 남기거나 file upload 에 마찬가지로 링크 추가 가능(자율)
    * 코드뷰 설명: 해당 논문 발표자는 다음주차에 코드뷰 설명(e.g, 어떤 라이브러리로 쉽게 쓸 수 있는지 usage 설명, 알고리즘이 복잡한 경우 코드뷰로 어떻게 구현되었는지 설명 등 본인 기호에 맞게)


---

### 참여자
> 강나경, 김소연, 김현지, 박기범, 임동진, 임수정, 정기원, 한나연 , 김은기

### 참고 링크
> 논문을 정리하는 틀과 issues를 통한 discussion이 좋았던 깃헙 레포 [참고](https://github.com/eubinecto/k4ji_ai/issues)
> 
> 리딩 리스트를 참고한 NLP Must Read paper 정리된 깃헙 레포 [참고](https://github.com/mhagiwara/100-nlp-papers)
> 
> 국내 NLP 리뷰 모임 [참고](https://github.com/jiphyeonjeon) (season1의 beginners에 중복되는 논문들 있어요!)
    
<!-- <details>
    <summary>기본 룰</summary>
    Foldable Content[enter image description here][1]
</details> -->
