+++
title = "About"
+++

## About Me

{{< figure class="avatar" src="/mac_avatar.webp" alt="avatar">}}

This is a Hugo based resume template. You can find the full source code on
[GitHub](https://github.com/ojroques/hugo-researcher).

## Research Interest

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam finibus ipsum
ac erat aliquam dapibus. Vestibulum vehicula placerat ex, a consectetur odio
pharetra quis[^1]. Mauris id urna ante.

Fusce pharetra diam ac nisi aliquet, velegestas ex iaculis. Pellentesque
laoreet cursus tellus sed pellentesque. Praesent a rhoncus elit[^2]. Nunc
ipsum nisl, consequat sit amet pretium quis, gravida id ipsum.

## Publications

In chronological order:
1. F.Bar, J.Doe: Effects of having a placeholder of a name
2. S.Holmes, J.Watson: Consequences of living with a sociopath in London

## Typography

This is a [link](http://google.com). Something *italics* and something **bold**.

---

<mark> maybe? WOW!!! how does that work when it's hard according to HC?</mark>

---

Here is a table:

Year | Award | Category
-----|-------|--------
2014 | Emmy  | Won Outstanding Lead Actor in a miniseries or a movie
2015 | BAFTA | Nominated for Best Leading Actor for Sherlock
2014 | Satellite | Won Best Actor miniseries or television film

Here is a horizontal rule:

---

Here is a blockquote:

> To a great mind, nothing is little

Here is a `code` block:

```python
def is_elementary():
  return True
```

<!-- annoying that it doesn't parse bash or shell properly but seems better as js! -->
```js
for i in *.zip
do if [ -e "$i.part" ]
then
  : # echo "$i still downloading"
else
  echo "processing $i"
  # ditto rather than unzip because ditto handles unicode filenames
  ditto -k -x $i $DESTDIR
  # rm $i # want to keep the files then hash this out.
  echo "processed $i"
fi
done
```



## References

* Foo Bar: Head of Department, Placeholder Names, Lorem
* John Doe: Associate Professor, Department of Computer Science, Ipsum

[^1]: This is the first footnote.
[^2]: This is the second footnote.
