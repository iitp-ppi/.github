## AI toolkits for prediction of structure-based protein interaction(바이오 및 신약 개발 연구에 활용될 수 있는 여러 단백질 상호작용 예측 AI 툴킷)
과학기술정보통신부 정보통신기획평가원 지원 사업
 - 오픈소스SW 및 DB는 전문 개발자의 연구 및 교육에 활용 가능함
 - 특정 단백질에 대한 바이오 및 신약 연구에 활용 가능한 예시 제공
### Database

[유기분자 결합구조 예측을 위한 DB](https://drive.google.com/file/d/1kQ_h9BSBs0pUX3soeVf-txPd5pWrz1wv/view?usp=sharing)

[단백질 결합구조 및 다중서열정렬 정보 학습 DB](https://ppi-interation.synology.me:5001/sharing/4euSTFcJY)

[단백질-유기분자](https://ppi-interation.synology.me/sharing/alFJx2yn0)/[단백질-단백질 변이의 기계학습을 위한 FEP DB](https://ppi-interation.synology.me/sharing/qypdaVISE)

### Documentation

[PPI Integration Toolkit 문서](https://iitp-ppi.github.io/PPI-Integration-Toolkit/)

### Toolkit list
#### List of modular toolkits
 - Toolkits for prediction of protein-protein interaction
   - [DeepFoldPublic](https://github.com/iitp-ppi/DeepFoldPublic): DeepFold protein structure prediction
   - [MiniWorld](https://github.com/iitp-ppi/MiniWorld): Minimal architecture for protein structure prediction
   - [BIS-ProteinStructure_libraries](https://github.com/iitp-ppi/ProteinStructure_libraries): toolkits dealing with protein data
   - [AlphaSS](https://github.com/iitp-ppi/AlphaSS): AlphaFold2 using SSbond embedding
   - [MSA_search_pipeline](https://github.com/iitp-ppi/MSA_search_pipeline): MSA search pipeline
 - Toolkits for prediction of protein-ligand interaction
   - [nurikit](https://github.com/iitp-ppi/nurikit): toolkits for ligand and protein manipulation
   - [DiffAlign](https://github.com/iitp-ppi/DiffAlign): diffusion model for ligand alignment
   - [BindingRMSD](https://github.com/iitp-ppi/BindingRMSD): evaluation model for protein-ligand model structure
   - [BAPred](https://github.com/iitp-ppi/BAPred): evaluation model for protein-ligand binding affinity
   - [galaxydock_dl](https://github.com/iitp-ppi/galaxydock_dl): protein-ligand docking model
   - [BsiteP](https://github.com/iitp-ppi/BsiteP): Protein-ligand binding site prediction
 - [PPI-Integration-Toolkit](https://github.com/iitp-ppi/PPI-Integration-Toolkit): integrated version of all toolkits
#### Template colab notebooks for integrated usage
 - Part 1 EGFR-antibody interaction analysis 
   - [Predicting protein-protein interactions](https://colab.research.google.com/drive/1wn6MHCFpBEoliHbFKLerlXRuDemUeBGw?usp=sharing)
 - Part 2 EGFR-ligand interaction analysis
   - [Predicting protein-ligand interactions](https://colab.research.google.com/drive/1FEp7VR21QKyYTeEgs2nhfoQLFjYGf09A?usp=sharing#scrollTo=7cto1uEPiW0z)
   - [Predicting the effect of protein mutations](https://drive.google.com/file/d/1G4RRI4ljbqXnnEYQF0sLtWCScx-MXGM0/view?usp=sharing)
