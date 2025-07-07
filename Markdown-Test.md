# Heading 1
Open md viewer in VS Code:
> ctrl + shift + v

instead of using `<br>` you can use `  ` (two spaces)

## Heading 2 a
Regular text

## Heading 2 b

**bold** not bold <br>
*italic* not italic

> block quote <br>
> new block quote different line

### Heading 3 starts a new line

and this is on another line <br>

<pre>
private void main() {
    private string func()
    {
        return "This is how to do inline code/code blocks";
    }
    Console.WriteLine(func());
}
</pre>

this is a new line of text after the inline code <br>

[Google](https://google.com) <br>

* unordered list
    * sub list item
        * sub sub list item
- also works as unordered list
    - same thing

1. ordered list
    1. sub ordered list
2. ordered list 2
    1. nested item

inline images: <br>
![a picture of Mario](https://upload.wikimedia.org/wikipedia/en/5/5c/Mario_by_Shigehisa_Nakaue.png)

new line starts after inline images <br>
"---" is a and text above it becomes like a heading 1
---

tables: <br>
| key | value |
|-----|-----|
|a|123456789101112131415|
|b|2|


images on GitHub
✅ Example with a local image in your repo: 
If you have a folder structure like: <br>
project/<br>
│<br>
├── README.md<br>
└── images/<br>
└── diagram.png<br>
Use a relative path: <br>
![System Diagram](images/diagram.png)