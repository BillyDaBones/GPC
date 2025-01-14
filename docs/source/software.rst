Software
========

.. _software:

This page contains all relevant info to each program used on the main laptop. It will not be fully comprehensive on how to use the software
as there are better documentation on specifics on their respective sites.

    .. |OBS| image:: https://raw.githubusercontent.com/BillyDaBones/GPC/v0.0.1/docs/source/assets/images/software/OBS.png
        :width: 100
        :alt: OBS Logo

    .. |FreeShow| image:: https://raw.githubusercontent.com/BillyDaBones/GPC/v0.0.1/docs/source/assets/images/software/FreeShow.png
        :width: 50
        :alt: FreeShow Logo

    .. |StreamDeck| image:: https://raw.githubusercontent.com/BillyDaBones/GPC/v0.0.1/docs/source/assets/images/software/StreamDeck_01.png
        :width: 50
        :alt: StreamDeck Logo

    .. |Companion| image:: https://raw.githubusercontent.com/BillyDaBones/GPC/v0.0.1/docs/source/assets/images/software/StreamDeck_02.png
        :width: 50
        :alt: Companion Logo


**OBS Studio**
--------------

|OBS|

`OBS Studio offical documentation <https://docs.obsproject.com/>`_


OBS Studio is our primary software for broadcasting GPC live streams and managing the foyer TV replay.

Before using OBS Studio for GPC purposes, I recommend familiarizing yourself with the software's basic features and interface. 
For newcomers, I recommend starting with this introductory tutorial to learn the essential controls and set up your first broadcast.

.. youtube:: nWbJJ4RnPx8


Audio
~~~~~

OBS Studio serves two primary use cases when it comes to audio:

* Live stream
* Foyer live replay

The live stream audio is fed in through from the USB audio interface, 
which OBS uses as the main source of audio.

The foyer live replay is utilizing a feature called audio "monitoring" in **Audio Mixer - Mic/Aux → ⋮ → Advanced Audio Properties** which, 
feeds the live stream audio into the computer's speakers.

.. note::
    The speaker that is set in the computer settings should be set to
    the HDMI output reffered to as **"Samsung TV"**, which is the 
    foyer TV. see :ref:`wiring` for more information.

Streaming
~~~~~~~~~

In **OBS Settings → Stream**, I've configured OBS to connect with SermonAudio's restreaming service. 
This is really useful because it lets us broadcast to multiple platforms simultaneously through a single stream setup.

.. image:: https://raw.githubusercontent.com/BillyDaBones/GPC/v0.0.1/docs/source/assets/images/software/Restream.png
    :width: 800
    :alt: Restreaming dashboard SermonAudio

Here's what that means in practice: When we stream through SermonAudio's platform, 
we can automatically broadcast to several different sites at once, including our `@GPCRedding <https://www.youtube.com/@GPCRedding>`_ 
YouTube channel. You can see all our active streaming destinations in the `SermonAudio dashboard <https://www.sermonaudio.com/dashboard/webcast/>`_

If you'd like to see how this works, `check out SermonAudio's demonstration video 
<https://www.sermonaudio.com/player/sermon/121211518553745/>`_ of their restreaming feature.

Scenes
~~~~~~

**Scenes** in OBS are different views in which the Live Stream can see the content.
A couple different scenes we have setup in OBS are

* **Slides**, which displays the slideshow on the livestream, and the webcam in the corner. Best used during music.
* **Wide**, which shows only the camera video and is the most used scene the stream will show.
* **Zoomed Pulpit**, which crops in the camera, intended to be used when zooming in the camera. See :ref:`operations_camera` for more about using the camera.



**FreeShow**
------------

|FreeShow|

`FreeShow Documentation <https://freeshow.app/docs/introduction/>`_


**Stream Deck (& Companion)**
-----------------------------

|StreamDeck|
|Companion|

`StreamDeck Quick Start <https://help.elgato.com/hc/en-us/articles/360028241291-Elgato-Stream-Deck-Quick-Start-Guide/>`_

`Companion (BitFocus) Documentation <https://bitfocus.io/companion/support/>`_

