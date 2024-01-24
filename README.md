# from-chava
# Siva Pavan Kumar Chava
## Shadab
My favourite restaurant is **Shadab**. The **exceptional taste palette** they present, coupled with the **initimate ambiance**, creates an ideal setting for a tranquil and enjoyable dining experience.

---
## Top Three Favorite Dishes

1. **First Preference:** Mutton 65
2. **Second Preference:** Chicken Fry Piece Biryani
3. **Third Preference:** Boti Kabab

- Charminar
- 50k Italian cafe & cafeteria
- The Nizams Museum 

![Look into MyMedia](MyMedia.md)

---

## My Foremost Suggestions
My top picks for the best telugu songs are shown in the table below. Also includes **Name**, **Reason** and **Composer**
|Name|Reason|Composer|
|---|---|---|
|Akhanda Title Song|This song has boasts of ethnic and western beats, and it leaves an impression of listening to a high-octane anthem rather than just a title song|Thaman S|
|Ramanna Ramanna|This song features a vast background score and, when we listen to it, depicts the Chowdary royalty|Mani Sharma|
|Mama Ek Peg Laa|The song is a celebration of life and friendship. It is a song about letting loose and having fun|Anup Rubens|
|One and Only Lion|The lyrics of the song are about heroism and strength. The music is also very energetic, which will help to create a fun and festive atmosphere|Mani Sharma|

---

## Favourite Quotes

> Where the mind is without fear and the head is held high.

> I slept and dreamt that life was joy. I awoke and saw that life was service. I acted and behold, service was joy.

Author Name : *Rabindranath Tagore*

---

## Code Fencing

The sample demonstrates how to define a structure using TypeScript interfaces ('MyInterface').
Based on the specified interface, an object ('myObject') is constructed.
To dynamically extract values from the object depending on keys, a function called ('getValue') is defined.
The function's use highlights the possible danger of utilizing invalid keys because TypeScript permits keys that are not included in the interface ('count').

```
interface MyInterface {
  id: number;
  name: string;
  properties: string[];
}

const myObject: MyInterface = {
  id: 1,
  name: 'foo',
  properties: ['a', 'b', 'c']
};

function getValue(value: keyof MyInterface) {
  return myObject[value];
}

getValue('id'); // 1
getValue('count')

```



