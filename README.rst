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

    :Название исследуемой задачи: Search for keywords by weak decoding
    :Тип научной работы: M1P
    :Автор: Иван Дмитриевич Морозов
    :Научный руководитель: д.т.н., профессор Местецкий Леонид Моисеевич

Abstract
========

В данной дипломной работе рассматривается двухэтапная задача: сначала распознавание рукописного текста, а затем выделение ключевых слов из текста с использованием методов слабой разметки. На первом этапе производится распознавание рукописных документов, что является ключевой задачей в области компьютерного зрения и обработки естественного языка. В процессе распознавания используется подход, основанный на современных нейросетевых моделях, позволяющих эффективно обрабатывать изображения рукописного текста и преобразовывать его в цифровую форму.

После успешного распознавания текста следующим шагом является выделение ключевых слов. В отличие от традиционных методов извлечения ключевых слов, которые требуют больших объемов вручную размеченных данных, предлагаемый подход использует методы слабой разметки. Слабая разметка позволяет обучать модели на данных с неполными или неточными метками, что значительно упрощает процесс подготовки обучающих наборов и делает его более гибким при работе с различными типами текстов.

Для выделения ключевых слов из распознанных текстов применяется метод слабой разметки, где ключевые слова выделяются на основе контекстных характеристик и предположений о важности терминов в зависимости от их появления и значимости в тексте. Такой подход позволяет повысить точность извлечения ключевых слов, несмотря на ограничения в разметке и возможные ошибки на этапе распознавания рукописного текста.

Работа включает эксперименты по сравнению предложенного подхода с традиционными методами, основанными на ручной разметке, с целью продемонстрировать преимущества слабой разметки в контексте извлечения ключевых слов из документов, содержащих рукописный текст.
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
