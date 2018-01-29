# CS-Task-1.3
Module Module1

    
    Sub Main()
        Dim Name As String
        Dim MemberIDNumber As String
        Dim NameToBeFound As String
        Dim Found As Boolean

        NameToBeFound = ""
        Name = ""
        MemberIDNumber = ""
        Found = False


        FileOpen(1, "E:\TextFileHandlingAssignment.txt", OpenMode.Input)

        Console.Write("The name of the Member : ")
        NameToBeFound = Console.ReadLine

        Name = UCase(NameToBeFound)
        Name = LCase(NameToBeFound)
        NameToBeFound = UCase(Name)
        NameToBeFound = LCase(Name)

        While EOF(1) = False
            Input(1, Name)
            Input(1, MemberIDNumber)

            If Name = NameToBeFound Then
                Console.WriteLine("The Member ID is : " & MemberIDNumber)
            Else
                Console.WriteLine("The Record was not found")
            End If
        End While

        Console.ReadKey()

    End Sub
