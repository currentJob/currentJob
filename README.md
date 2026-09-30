<div align="center">

## 안녕하세요, CurrentJob입니다

컴퓨터 비전 모델을 만들고 배포하는 일을 주로 합니다.<br>
요즘은 브라우저에서 바로 돌아가는 AI 서비스와 LLM 에이전트를 만들고 있습니다.

[![Portfolio](https://img.shields.io/badge/Portfolio-222222?style=for-the-badge&logo=githubpages&logoColor=white)](https://currentjob.github.io/portfolio-github-pages/)
[![Tech Blog](https://img.shields.io/badge/Tech_Blog-16735D?style=for-the-badge&logo=rss&logoColor=white)](https://currentjob.github.io/devops-pipeline/)

</div>

## 주요 기술

- 컴퓨터 비전: YOLO, OCR, AutoEncoder 모델 개발과 ONNX 변환, Triton 배포
- 브라우저 AI: WebGPU, ONNX Runtime Web, Transformers.js로 서버 없이 추론
- LLM 에이전트: Claude, OpenAI API 기반 멀티 에이전트와 LangGraph 워크플로
- MLOps: Docker, Kubernetes, GitHub Actions로 서비스 운영
- 웹 개발: FastAPI, Django, Flask, Spring Boot 백엔드와 React 프론트엔드

## 프로젝트

### 브라우저에서 동작하는 AI

| 프로젝트 | 내용 | 주소 |
|---|---|:---:|
| [local-code-review](https://github.com/currentJob/local-code-review) | git diff를 붙여 넣으면 브라우저 안에서 Qwen2.5-Coder 1.5B가 코드 리뷰를 해 줍니다. | [링크](https://currentjob.github.io/local-code-review/) |
| [ocr-llm-page](https://github.com/currentJob/ocr-llm-page) | PP-OCRv5로 한국어 이미지를 읽고 LLM으로 요약합니다. 다른 사이트에서 가져다 쓸 수 있는 OCR 모듈도 함께 배포합니다. | [링크](https://currentjob.github.io/ocr-llm-page/) |
| [yolov8-seg-page](https://github.com/currentJob/yolov8-seg-page) | YOLOv8-seg 모델을 ONNX로 변환해 Web Worker에서 추론하고 마스크를 보여 줍니다. | [링크](https://currentjob.github.io/yolov8-seg-page/) |

### 모델 서빙과 인프라

| 프로젝트 | 내용 | 주소 |
|---|---|:---:|
| [triton-grpc-ocr](https://github.com/currentJob/triton-grpc-ocr) | PaddleOCR 모델을 NVIDIA Triton으로 서빙하고 gRPC 게이트웨이와 FastAPI로 연결했습니다. 비동기 작업 큐와 RAG 검색을 포함합니다. | [링크](https://currentjob.github.io/triton-grpc-ocr/) |
| [devops-pipeline](https://github.com/currentJob/devops-pipeline) | 기술 블로그와 인프라 구성 저장소입니다. CI/CD, GHCR, Kubernetes 배포, Prometheus와 Grafana 모니터링을 다룹니다. | [블로그](https://currentjob.github.io/devops-pipeline/) |

### LLM 에이전트와 웹 서비스

| 프로젝트 | 내용 | 주소 |
|---|---|:---:|
| [langchain-monitoring](https://github.com/currentJob/langchain-monitoring) | 공장 설비 모니터링 시스템입니다. LangGraph로 센서 이상을 분석하고 조치를 제안하며, WebSocket 대시보드로 상태를 보여 줍니다. | |
| [city-walk-planner](https://github.com/currentJob/city-walk-planner) | 도시를 고르면 지도 위에 하루 동선을 짜 주는 여행 플래너입니다. 동행과 일정, 경비를 함께 관리할 수 있습니다. | [링크](https://currentjob.github.io/city-walk-planner/) |

## 기술 스택

**AI / ML**<br>
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO-111F68?style=flat&logo=yolo&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat&logo=onnx&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat&logo=anthropic&logoColor=white)
![WebGPU](https://img.shields.io/badge/WebGPU-005A9C?style=flat&logo=webgpu&logoColor=white)

**Serving / MLOps**<br>
![NVIDIA Triton](https://img.shields.io/badge/Triton-76B900?style=flat&logo=nvidia&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244C5A?style=flat)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)

**Backend / Frontend**<br>
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white)
