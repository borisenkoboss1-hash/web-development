# Dina Borisenko

## Contact Information
- **Phone:** +375 (29) 123-45-67
- **Email:** dina.borisenko@example.com
- **GitHub:** [github.com/dinaborisenko](https://github.com/dinaborisenko)


## About Me
I am a second-year university student specializing in Software Development. I am motivated to learn new technologies and improve my skills every day.

## Skills
- HTML, CSS (basic)
- C++ (basic)
- Git, GitHub
- Markdown


English Language
Level: Beginner-Intermediate (A2-B1)
Can understand simple texts and conversations
Can communicate on basic topics
Actively learning through:
English classes at university
Watching programming tutorials in English
Reading technical documentation with translation help

Code Examples
```csharp
using System;

namespace ArraySorting
{
    class Program
    {
        static void Main(string[] args)
        {
            int[] numbers = { 64, 34, 25, 12, 22, 11, 90 };
            
            Console.WriteLine("Original array:");
            PrintArray(numbers);
            
            BubbleSort(numbers);
            
            Console.WriteLine("\nSorted array:");
            PrintArray(numbers);
        }
        
        static void BubbleSort(int[] arr)
        {
            int n = arr.Length;
            for (int i = 0; i < n - 1; i++)
            {
                for (int j = 0; j < n - i - 1; j++)
                {
                    if (arr[j] > arr[j + 1])
                    {
                        // Swap elements
                        int temp = arr[j];
                        arr[j] = arr[j + 1];
                        arr[j + 1] = temp;
                    }
                }
            }
        }
        
        static void PrintArray(int[] arr)
        {
            foreach (int num in arr)
            {
                Console.Write(num + " ");
            }
            Console.WriteLine();
        }
    }
}
```
## Hobbies & Interests

### Drawing
In my free time, I enjoy drawing and sketching. I like to create both traditional pencil drawings and digital art. Drawing helps me develop my creativity and attention to detail - skills that are also important in programming.

### Photography
I love taking photos of nature, architecture, and everyday moments. Photography teaches me to see the beauty in ordinary things and pay attention to composition and lighting. I use a simple camera and sometimes edit photos on my computer.
