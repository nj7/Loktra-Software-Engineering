## Full Stack Engineer Programming Task

In order to be considered for the full stack engineer position, you must complete the following steps. 

*Note: This task should take no longer than 1-2 hours at the most.*


## Task

Write code to find a 9 letter string of characters that contains only letters from

`acdegilmnoprstuw`

such that the hash(the_string) is

`930846109532517`

if hash is defined by the following pseudo-code:

```
Int64 hash (String s) {
    Int64 h = 7
    String letters = "acdegilmnoprstuw"
    for(Int32 i = 0; i < s.length; i++) {
        h = (h * 37 + letters.indexOf(s[i]))
    }
    return h
}
```

For example, if we were trying to find the 7 letter string where `hash(the_string)` was `680131659347`, the answer would be "leepadg".

To apply, please email akhil@loktra.com with your solution as the first word in the subject line. Include link of your code on Github, and also send us a current resume in HTML, Plain Text, or PDF format. In the body of the email please explain why you would be a good fit for this job.
