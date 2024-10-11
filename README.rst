|test| |codecov| |docs|

.. |test| image:: https://github.com/intsystems/ProjectTemplate/workflows/test/badge.svg
    :target: https://github.com/intsystems/ProjectTemplate/tree/master
    :alt: Test status
    
.. |codecov| image:: https://img.shields.io/codecov/c/github/intsystems/ProjectTemplate/master
    :target: https://app.codecov.io/gh/intsystems/ProjectTemplate
    :alt: Test coverage
    
.. |docs| image:: https://github.com/intsystems/ProjectTemplate/workflows/docs/badge.svg
    :target: https://intsystems.github.io/ProjectTemplate/
    :alt: Docs status


.. class:: center

    :Название исследуемой задачи: Адаптация больших языковых моделей для работы с научными текстами - Large Language Models adaptation for scientific domain
    :Тип научной работы: M1P
    :Автор: Максим Сергеевич Крыжановский
    :Научный руководитель: доктор физико-математических наук, Константин Вячеславович Воронцов
    :Научный консультант(при наличии): степень, Фамилия Имя Отчество

Abstract
========

Large Language Models (LLMs) have demonstrated exceptional capabilities across a variety of domains, but adapting them to specialized fields such as the scientific domain remains a challenge. While ample scientific corpora are available for fine-tuning, there is a significant lack of high-quality datasets for alignment tasks. To address this, we propose a novel framework for Large Language Model adaptation in the scientific domain. Our approach leverages contrastive learning to fine-tune a transformer model specifically for scientific text generation. To overcome the alignment data scarcity, we introduce a distillation process from a pre-aligned LLM into our fine-tuned model, ensuring robust alignment to scientific language conventions. The resulting model is smaller, more efficient, and well-aligned with the scientific domain, achieving comparable performance to larger LLMs. This method offers an efficient pathway for developing specialized LLMs in domains with limited alignment datasets, pushing the boundaries of LLM adaptability in specialized fields.

Research publications
===============================
1. 

Presentations at conferences on the topic of research
================================================
1. 

Software modules developed as part of the study
======================================================
1. A python package *mylib* with all implementation `here <https://github.com/intsystems/ProjectTemplate/tree/master/src>`_.
2. A code with all experiment visualisation `here <https://github.comintsystems/ProjectTemplate/blob/master/code/main.ipynb>`_. Can use `colab <http://colab.research.google.com/github/intsystems/ProjectTemplate/blob/master/code/main.ipynb>`_.
