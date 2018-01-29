# CS-Task-1.2
  Sub Main()
        Dim Name As String
        Dim MemberIDNumber As String

        FileOpen(1, "E:\TextFileHandlingAssignment.txt", OpenMode.Input)

        While EOF(1) = False
            Console.Write("The Name : " & Name)
            Console.Write("Member ID : " & MemberIDNumber)

        End While


    End Sub

End Module
