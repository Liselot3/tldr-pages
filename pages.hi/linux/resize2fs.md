# resize2fs

> ext2, ext3 या ext4 फाइल सिस्टम का आकार बदलें।
> यह अंतर्निहित पार्टीशन का आकार नहीं बदलता है। फाइल सिस्टम को पहले अनमाउंट करना पड़ सकता है, अधिक जानकारी के लिए मैन पेज पढ़ें।
> अधिक जानकारी: <https://manned.org/resize2fs>।

- स्वचालित रूप से फाइल सिस्टम का आकार बदलें:

`resize2fs {{/dev/sdXN}}`

- 40G के आकार में फाइल सिस्टम का आकार बदलें, प्रगति बार दिखाते हुए:

`resize2fs -p {{/dev/sdXN}} {{40G}}`

- फाइल सिस्टम को उसके न्यूनतम संभव आकार में सिकोड़ें:

`resize2fs -M {{/dev/sdXN}}`