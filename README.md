# CS-Task-1.4
Module Module1

    Sub Main()
            Dim telephone As String
        Dim StartDate As Date

        Name = ""
        MemberIDNumber = ""
        telephone = ""

        FileOpen(1, "E:\TextFileHandlingAssignment.txt", OpenMode.Input)
        While EOF(1) = False
            Console.WriteLine("Enter the Name of the member : " & Name)
            Name = Console.ReadLine

            Console.WriteLine("Enter the Member ID Number : " & MemberIDNumber)
            MemberIDNumber = Console.ReadLine

            Console.WriteLine("Enter the Telephone number ")
            telephone = Console.ReadLine

            Console.WriteLine("Enter the Fist date of membership: ")
            StartDate = Console.ReadLine

        End While
        
        FileOpen(2, "E:\Temp.txt", OpenMode.Output)

        WriteLine(2, Name)
        WriteLine(2, MemberIDNumber)
        WriteLine(2, telephone)
        WriteLine(2, StartDate)

        Console.ReadKey()

    End Sub

End Module
