# Conda Environment Collection

이 레포지토리는 자주 사용하는 개발/연구용 Conda 환경을 모아 정리한 공간입니다.  
`environment.yaml` 파일을 통해 손쉽게 동일한 환경을 재구성할 수 있습니다.

---

## 📁 Repository Structure

envs/  
├── miniROCKET/  
│   └── environment.yaml  
│   └── mROCKET_GUIDE_##.ipynb  
├── SVM/  
│   └── (생략)environment.yaml  
│   └── plot  
├── ~/  
│   └── environment.yaml  
├── ~/  
│   └── environment.yaml  
└── ...  

---

## 환경 저장 및 생성

```bash
conda env export > environment.yaml   # export env
conda env create -f environment.yaml  # load env
conda activate <env-name>             # activate env
```
