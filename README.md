# CS-Task-1.1
Module Module1
    
    Sub Main()
        Dim Name As String
        Dim MemberIDNumber As String
        Dim EndFile As String

        FileOpen(1, "E:\TextFileHandlingAssignment.txt", OpenMode.Output)

        

        Do
            Console.WriteLine("Enter the Name of the member : ")
            Name = Console.ReadLine
            WriteLine(1, Name)

            Console.WriteLine("Enter the Member ID Number : ")
            MemberIDNumber = Console.ReadLine
            WriteLine(1, MemberIDNumber)


            Console.Write(" Want to end this file?")
            EndFile = Console.ReadLine
            EndFile = UCase(EndFile)
            EndFile = LCase(EndFile)
        Loop Until EndFile = "yes"





    End Sub



End Module
