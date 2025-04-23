# semantic_database_for_monghaengrok

# semantic_database_for_monghaengrok
# 몽행록 시맨틱 그래프 데이터베이스 / Semantic Graph Database for Monghaengrok

이 저장소는 불가 유람기 ｢몽행록｣의 시맨틱 구조를 Neo4j 그래프 데이터베이스로 구축한 결과물을 공유합니다.  
This repository shares the semantic graph database of Buddhist travelogue *Monghaengrok* built with Neo4j.

---

## 📁 파일 구성 / File Structure

| 파일명 / Filename                | 설명 / Description                                                                                   |
|----------------------------------|-----------------------------------------------------------------------------------------------------|
| `Class and Relation.xlsx`        | 시맨틱 데이터베이스에서 설계한 클래스 및 관계 정보 / Classes and relations defined for the data model   |
| `Nodes and Links/`               | CSV 파일 모음 (노드 및 링크 데이터) / Collection of node and link CSV files used for import           |
| `neo4j_monghaengrok.json`        | Neo4j에서 export한 노드 정보 / Exported node data from Neo4j                                         |

---

## 🧾 데이터 설명 / Data Description

- **데이터 출처 / Data Source**: ｢몽행록｣의 시맨틱 구조를 분석하여 스프레드시트 기반으로 정리한 후 Neo4j에 임포트하여 시각화 및 분석을 수행하였습니다.  
  *The semantic structure of *Monghaengrok* was analyzed and structured in spreadsheet format, then imported into Neo4j for visualization and analysis.*

- **데이터 모델 설계 해설 / Documentation of the Data Model**:

  이 데이터베이스 모델에 대한 자세한 설명은 다음 논문을 참조하세요:  
  *For a detailed description of the database model, see the following paper:*
 
  장지훈, ｢『설담집』 ｢몽행록｣의 시맨틱 데이터 모델 설계｣, 『한국문학연구』 제77집, 동국대학교 한국문학연구소, 2025.  
  *Jang, Jihoon. "Semantic Data Model Design for Monghaengrok in Seoldamjip."* *The Studies in Korean Literature*, no. 77, Dongguk University, 2025.

---

이 데이터는 비상업적 연구 및 교육 목적으로 자유롭게 사용할 수 있습니다.
This data is freely available for non-commercial research and educational purposes.

GitHub Issues 혹은 E-mail(7wkdwlgns7@naver.com)을 통해 문의해주세요.
Please contact me via GitHub Issues or by email at 7wkdwlgns7@naver.com.
