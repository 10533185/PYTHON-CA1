# PYTHON-CA1
class record:      
    
    def add(self,student):
        self.student=student        
        return self.student
    
    def retrieve(self):
        if self.student[0][0]<self.student[1][0] and self.student[0][0]<self.student[2][0]:
            return self.student[0]
        
    
data=[[10000001,"Arun","code001"],[10000002,"vijay","code001"],[10000003,"Anand","code001"]]
r=record()
r.add(data)
r.retrieve()
print(len(data))
