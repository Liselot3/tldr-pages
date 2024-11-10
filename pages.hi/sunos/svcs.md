# svcs

> चल रहे सेवाओं के बारे में जानकारी सूचीबद्ध करें।
> अधिक जानकारी: <https://www.unix.com/man-page/linux/1/svcs>।

- सभी चल रही सेवाओं की सूची बनाएं:

`svcs`

- उन सेवाओं की सूची बनाएं जो चल नहीं रही हैं:

`svcs -vx`

- किसी सेवा के बारे में जानकारी सूचीबद्ध करें:

`svcs apache`

- सेवा लॉग फ़ाइल के स्थान को दिखाएं:

`svcs -L apache`

- सेवा लॉग फ़ाइल के अंत को प्रदर्शित करें:

`tail $(svcs -L apache)`