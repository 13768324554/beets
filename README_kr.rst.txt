.. image:: http://img.shields.io/pypi/v/beets.svg
    :target: https://pypi.python.org/pypi/beets

.. image:: http://img.shields.io/codecov/c/github/beetbox/beets.svg
    :target: https://codecov.io/github/beetbox/beets

.. image:: https://travis-ci.org/beetbox/beets.svg?branch=master
    :target: https://travis-ci.org/beetbox/beets


beets
=====

Beets�� �������� ������ ��� ������� ���� �̵�� ���̺귯�� ���� �ý����̴�.

Beets�� ������ ���ǵ��� �ѹ��� �� �޴� ���̴�.
���ǵ��� īŻ�α�ȭ �ϰ�, �ڵ����� ��Ÿ �����͸� �����Ѵ�.
�׸��� ���ǿ� �����ϰ� ������ �� �ִ� �������� �����Ѵ�.

������ Beets�� binary tag corrector�� �� ���� �����̴�.

  $ beet import ~/music/ladytron
  Tagging:
      Ladytron - Witching Hour
  (Similarity: 98.4%)
   * Last One Standing      -> The Last One Standing
   * Beauty                 -> Beauty*2
   * White Light Generation -> Whitelightgenerator
   * All the Way            -> All the Way...

Beets�� ���̺귯���� ������ �Ǿ��� ������, �ϰ� ���ǵ鿡 ���� ����ϴ� ��� ���� �� �� �ִ�.
`plugins`_�� ���ؼ� ��� ���� �� �� �ִ� ���̴�!

- �ʿ��ϴ� ��Ÿ �����͸� ����ϰų� ��ġ �� ��: `album art`_,
  `lyrics`_, `genres`_, `tempos`_, `ReplayGain`_ levels, or `acoustic
  fingerprints`_.
- `MusicBrainz`_, `Discogs`_, `Beatport`_�κ��� ��Ÿ�����͸� �������ų�, 
  �뷡 �����̳� ���� Ư¡���� ��Ÿ�����͸� �����Ѵ�
- `Transcode audio`_ �ϰ� �����ϴ� � �������ε� �����Ѵ�.
- ���� ���̺귯������ `duplicate tracks and albums`_�̳� `albums that are missing tracks`_�� �˻��Ѵ�.
- ���� ����ų�, ���� ���� ������ ���� ����� �±׵��� �����.
- ������ ��Ÿ�����Ϳ��� �ٹ� ��Ʈ�� �����̳� �����Ѵ�.
- ���� ���ǵ��� `HTML5 Audio`_�� ����Ͽ� � �������� ����� �� �ְ�,
  �� �������� ǥ�� �� �� �ִ�.
- ��ɾ�κ��� ���� ������ ��Ÿ�����͸� �м��� �� �ִ�.
- `MPD`_ ���������� ����Ͽ� ���� �÷��̾�� ������ ������, ��û���� �پ��� �������̽��� �۵��Ѵ�.

���� Beets�� �ϰ� ���ϴ°� ���� ���ٸ�, 
�ϰ� python�� �ȴٸ� `writing your own plugin`_�� ���������� �����ϴ�.

.. _plugins: http://beets.readthedocs.org/page/plugins/
.. _MPD: http://www.musicpd.org/
.. _MusicBrainz music collection: http://musicbrainz.org/doc/Collections/
.. _writing your own plugin:
    http://beets.readthedocs.org/page/dev/plugins.html
.. _HTML5 Audio:
    http://www.w3.org/TR/html-markup/audio.html
.. _albums that are missing tracks:
    http://beets.readthedocs.org/page/plugins/missing.html
.. _duplicate tracks and albums:
    http://beets.readthedocs.org/page/plugins/duplicates.html
.. _Transcode audio:
    http://beets.readthedocs.org/page/plugins/convert.html
.. _Discogs: http://www.discogs.com/
.. _acoustic fingerprints:
    http://beets.readthedocs.org/page/plugins/chroma.html
.. _ReplayGain: http://beets.readthedocs.org/page/plugins/replaygain.html
.. _tempos: http://beets.readthedocs.org/page/plugins/acousticbrainz.html
.. _genres: http://beets.readthedocs.org/page/plugins/lastgenre.html
.. _album art: http://beets.readthedocs.org/page/plugins/fetchart.html
.. _lyrics: http://beets.readthedocs.org/page/plugins/lyrics.html
.. _MusicBrainz: http://musicbrainz.org/
.. _Beatport: https://www.beatport.com

��ġ
-------

�ʴ� ``pip install beets``�� ����ؼ� Beets�� ��ġ�� �� �ִ�.
�׸��� `Getting Started`_ ���̵带 Ȯ���� �� �ִ�.

.. _Getting Started: http://beets.readthedocs.org/page/guides/main.html

��Ʈ�����
----------

��� ��������� �˰�ʹٸ� `Hacking`_ ��Ű�������� Ȯ���϶�.
�ʴ� docs �ȿ� `For Developers`_���� ������ ������ �ִ�.

.. _Hacking: https://github.com/beetbox/beets/wiki/Hacking
.. _For Developers: http://docs.beets.io/page/dev/

Read More
---------

`its Web site`_���� Beets�� ���� ���� �� �˾ƺ� �� �ִ�. 
Ʈ���Ϳ��� `@b33ts`�� �ȷο��ϸ� �� �ҽ��� �� �� �ִ�.

.. _its Web site: http://beets.io/
.. _@b33ts: http://twitter.com/b33ts/

���ڵ�
-------

`Adrian Sampson`_ �� ���� ������� ������ �޾� Beets�� �������.
���� �ʹٸ� `forum`_.�� �湮�ϸ� �ȴ�.

.. _forum: https://discourse.beets.io
.. _Adrian Sampson: http://www.cs.cornell.edu/~asampson/
