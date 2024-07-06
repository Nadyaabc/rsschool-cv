# Nadzeya Zhohla

### Contact Info

- **Location** : Minsk, Belarus
- **Telegram** : [@nadya_a_a_a](https://t.me/nadya_a_a_a)
- **e-mail** :  nadyash295923@gmail.com
- **GitHub** : [Nadyaabc](https://github.com/Nadyaabc)
- **LinkedIn** : [Nadzeya Zhohla](https://by.linkedin.com/in/nadzeya-zhohla-ba4874271)

### Summary
I am currently a third year student at Belarusian State University of Informatics and Radioelectronics.
My goal is to become a software developer.
I am interested in Java and Back-End development

### Skills
* Java
* C++
* Git
* MySQL
* HTML
* CSS

### Code example
There is a sentence with words and numbers. The sentence splitted to the array of Strings which is called WORDS. Complete the code, parse integers, calculate the sum of numbers in the WORDS, also join strings with space delimiter

    public static void main(String[] args) {
        Iterator<String> words = WORDS.iterator();
        int sum = 0;
        String justWords = "";
        while (words.hasNext()) {
            String next = words.next();
            try {
                int number = Integer.parseInt(next);
                sum += number;
            }
            catch (NumberFormatException e) {
                justWords += " " + next;
            }
        }
        System.out.println("Sum is " + sum);
        System.out.println("Just words:" + justWords);
    }

### Education
- Belarusian State University of Informatics and Radioelectronics (BSUIR)
  (2022-2026) Automated information processing and control systems

### Languages
* English - *C1*
* Russian - *Native Speaker*
* Belarusian - *Native Speaker* 
