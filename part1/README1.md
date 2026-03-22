# 🚩 Phase 1: Deep Learning Foundations
딥러닝의 가장 핵심이 되는 '기울기(Gradient)'의 원리를 파악하고, 수식을 코드로 옮기는 능력을 배양합니다.

### 📔 학습 리포트
| 주차 | 핵심 내용 | 주요 달성 성과 |
| :--- | :--- | :--- |
| **W1** | **Linear Regression** | `LMS` 손실 함수 정의 및 다변수(Multivariate) 데이터 처리 |
| **W2** | **Logistic Regression** | `Sigmoid` 미분 유도 및 결정 경계(Decision Boundary) 시각화 |
| **W3** | **PyTorch Mastery** | `Tensor` 조작법 익히기 및 `nn.Module` 커스텀 모델 구현 |

### 🌟 Key Highlights (Phase 1)
* **Math to Code**: `week2_gradient_ref.pdf`를 통해 유도한 BCE Loss 미분 수식을 직접 NumPy 코드로 구현 성공.
* **From Scratch**: 라이브러리 도움 없이 `weight`와 `bias`를 직접 업데이트하는 학습 루프(Training Loop) 설계.
* **Framework Migration**: NumPy로 구현한 로직을 PyTorch의 `loss.backward()`와 `optimizer.step()`으로 치환하며 생산성 향상 경험.

### 🧪 실습 환경 검증
- 모든 코드는 `test.ipynb`를 통해 PyTorch 2.10+ 및 CPU/GPU 환경에서 호환성을 검증함.
- `[solution]` 파일을 별도로 관리하여 학습의 정답셋을 확보함.

[← 메인 화면으로 돌아가기](../README.md)