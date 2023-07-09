# Mary Deulina

## Contact details:

Rs-school Discord: *Mary Deulina (@Amelisssa)*
Email: *mariadeulina@mail.ru*
Telegram: *@sweetpotato234*

## Skills:

* HTML, CSS
* PostgreSQL
* C# (basic)
* Java (basic)
* Git, GitHub

## Code example:

Given a one-dimensional array A consisting of 2n elements. Rearrange the array elements as follows:
a[n+1], a[n+2], ...,a[2n], a[1], a[2], ..., a[n] 

```
public class Task {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter array size: ");
        int n  = sc.nextInt();
        int[] array = new int[n * 2];

        for (int i = 0; i < array.length; i++) {
            array [i]= i + 1;
        }

        System.out.println("Original array: " + Arrays.toString(array));
        int[] array2 = new int[2 * n];
        for (int i = 0; i < n; i++) {
            array2[i] = array[i + n];
            array2[i + n] = array[i];
        }
        System.out.println("Rearranged array: " + Arrays.toString(array2));
    }
    }
```

## Education and courses:

- Mathematical software and administration of information systems: programming and big data analysis technologies. Tyumen State University. 2021-2025 (in progress)

- RS Schools Course «JavaScript/Front-end. Stage 0» (in progress)

## Languages:

Russian - native
English - C2 (Proficient)
Deutsch - A1