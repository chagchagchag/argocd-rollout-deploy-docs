---
title: Introduction
description: 'Introduce'
category: 'Getting started'
position: 98
---

<alert type="success">

이 블로그는 ArgoCD 를 활용해서 Blue/Green, Canary 등과 같은 무중단 배포를 수행하는 방식들을 정리한 예제입니다. 가급적 백엔드 개발자 관점에서 자신이 개발한 리소스를 어떻게 배포해야 하는지를 정리했습니다. 따라서 로컬 개발 PC에 Kind 라는 클러스터를 설치하고, 원하는 k8s 애플리케이션의 무중단 배포를 ArgoCD를 이용해 진행하는 과정에 대해서만 다룹니다.
<br>

EKS나 AWS 내의 ALB, Public Subnet, AWS에 ingress-nginx 연동 설정 등등 세부적인 인프라 벤더 설정에 대한 내용은 이번 블로그의 문서 정리 범위에서 배제했습니다.
<br>

기회가 된다면 별도의 github page 에 정리할 예정이지만, 이번 github page 에서는 가급적 백엔드 개발 범위에만 한정해서 문서를 작성했습니다.
<br>

</alert>

## Features

<list :items="features"></list>

<p class="flex items-center">Enjoy a documentation with light and dark mode:&nbsp;<color-switcher class="inline-flex ml-2"></color-switcher></p>
