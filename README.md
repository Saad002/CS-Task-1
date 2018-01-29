# CS-Task-1.4
Module Module1

    Sub Main()
        Dim Name As String
        Dim MemberIDNumber As String
       
        Console.WriteLine("Enter the Name of the member : ")
        Name = Console.ReadLine

        Console.WriteLine("Enter the Member ID Number : ")
        MemberIDNumber = Console.ReadLine

        FileOpen(1, "E:\TextFileHandlingAssignment.txt", OpenMode.Append)

        WriteLine(1, Name)
        WriteLine(1, MemberIDNumber)
         

        Console.ReadKey()

    End Sub

End Module
