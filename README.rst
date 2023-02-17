Certifi: 파이썬 SSL 인증서
================================

Certifi는 Mozilla가 엄선한 루트 인증서 모음을 제공합니다.
SSL 인증서의 신뢰성을 검증하는 동시에 TLS 호스트의 신원을 확인하기 위해
신원을 확인합니다. 'Requests`_프로젝트에서 추출했습니다.

설치
------------

'``certifi``는 PyPI에서 사용할 수 있습니다. 'pip``:'로 설치하기만 하면 됩니다:

    $ pip install certifi

사용법
-----

설치된 인증 기관(CA) 번들을 참조하려면, 내장함수를 사용할 수 있습니다.
내장 함수::

    >>> import certifi

    >>> certifi.where()
    '/usr/local/lib/python3.7/site-packages/certifi/cacert.pem'

또는 명령줄에서 다음과 같이 합니다:

    $ python -m certifi
    /usr/local/lib/python3.7/site-packages/certifi/cacert.pem

즐기세요!

.. _`Requests`: https://requests.readthedocs.io/en/master/

인증서 추가/제거
--------------------------------

Certifi는 추가/제거 또는 기타 수정은 지원하지 않습니다.
추가/제거 또는 기타 수정을 지원하지 않습니다. 이 프로젝트는 신뢰할 수 있고
신뢰할 수 있고 이식성이 뛰어난 신뢰 루트를 제공하기 위한 것입니다. 대체 신뢰를 사용하는 방법은 업스트림 프로젝트
에서 대체 신뢰를 사용하는 방법을 확인하세요.


Translated with www.DeepL.com/Translator (free version)
