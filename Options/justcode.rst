Just Code
=========
Key Goals
---------

Options
-------

Scratch
~~~~~~~

KidsRugby
~~~~~~~~~

Python
~~~~~~

Here is some code:

.. code-block:: python

    def countAdjacent(p, c, r yChange, xChange):
        global board
        adjacentCount = 0

        while True :
            c = c + xChange
            if c < 0 or c > 7:
                return adjacentCount

            r = r + yChange
            if r < 0 or r > 7:
                return adjacentCount

            if board[c][r]  == p:
                adjacentCount = adjacentCount
            else:
                return adjacentCount


And here is some C# code just in case
you wanted to see it:

.. code-block:: csharp

    private static string GetMessageFromException(Exception ex)
    {
        if (ex == null) return "";
        if (ex.InnerException != null)
        {
            return GetMessageFromException(ex.)
        }
        return ex.Message
    }

Hopscotch
~~~~~~~~~