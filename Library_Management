class library_item:
    def __init__(self,id,title,year):
        self._id=id
        self.title=title
        self.year=year
    def getid(self):
        return self._id
    def gettitle(self):
        return self.title
    def getyear(self):
        return self.year
class book(library_item):
    def __init__(self,id,title,year,author):
        super().__init__(id,title,year)
        self.author=author
    def setauthor(self,n):
        self.author=n
    def getauthor(self):
        return self.author
class magazine(library_item):
    def __init__(self,id,title,year,issue):
        super().__init__(id,title,year)
        self.issue=issue
    def getissue(self):
        return self.issue
item=library_item(5,"pp",2023)
Book=book(2,"ded",303,"jj")
Book.setauthor("kk")
print(Book.getid())
mag=magazine(1,"python",223,2)
print(f"book:{mag.getyear()} \nissue:{mag.getissue()}")
