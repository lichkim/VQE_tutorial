# VQE(Variational Quantum Eigensolver) 튜토리얼

이 저장소는 양자 머신러닝의 핵심 알고리즘 중 하나인 VQE(Variational Quantum Eigensolver)를 이해하고 직접 구현해볼 수 있도록 구성된 튜토리얼입니다. VQE를 이용하여 분자의 바닥 상태 에너지(ground state energy)를 계산하는 과정을 단계별로 학습합니다.

## 🚀 소개

**VQE**는 양자 컴퓨터와 고전 컴퓨터의 장점을 결합한 하이브리드 양자-고전 알고리즘입니다. 이 튜토리얼에서는 **Qiskit** 라이브러리를 사용하여 수소($H_2$) 분자의 바닥 상태 에너지를 계산하는 전체 과정을 다룹니다.

**학습 목표:**
* VQE 알고리즘의 작동 원리 이해
* Qiskit을 이용한 양자 회로(Ansatz) 및 해밀토니안(Hamiltonian) 구성
* 고전 최적화기(Classical Optimizer)를 활용한 에너지 최소화 과정 실습

## 사용 방법

Jupyter Notebook을 실행하여 튜토리얼을 단계별로 따라 진행할 수 있습니다.
