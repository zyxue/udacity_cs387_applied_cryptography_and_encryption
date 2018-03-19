**Counter mode hash illustration**
![counter mode hash illustration](https://github.com/zyxue/udacity_cs387_applied_cryptography_and_encryption/blob/master/ps2/quiz5_hash_collision/counter_mode_hash_illustration.png?raw=true)


Example output:

```
$python2  hash_collision.py 
original message:
	Trust, but verify. -a signature phrase of President Ronald Reagan
another message with hash collision:
	2??Q~Ԇ??
                Z?|?J??k??4?|?
                              phrase of President Ronald Reagan
original message:
	The best way to find out if you can trust somebody is to trust them. (Ernest Hemingway)
another message with hash collision:
	-?????"?
?z?Jcan trust somebody is to trust them. (Ernest Hemingway)
original message:
	If you reveal your secrets to the wind, you should not blame the wind for revealing them to the trees. (Khalil Gibran)
another message with hash collision:
	>?z??3?.??p??$?^?.?e wind, you should not blame the wind for revealing them to the trees. (Khalil Gibran)
original message:
	I am not very good at keeping secrets at all! If you want your secret kept do not tell me! (Miley Cyrus)
another message with hash collision:
	$?kԞ3?R?.??????"?^?.?crets at all! If you want your secret kept do not tell me! (Miley Cyrus)
original message:
	This message is exactly sixty four characters long and no longer
another message with hash collision:
	.??k??v?
                C?.??????%?\?g?Jur characters long and no longer
```

Unsurprisingly, swapping blocks creates nonsensical characters.


Solution video at https://www.youtube.com/watch?v=QT0kt7_BBVI
