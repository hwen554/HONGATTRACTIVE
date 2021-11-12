# HONGATTRACTIVE
Hi there!
class Myself:
    def __init__(self,name="HongWeng,languages="Javascript,java,python,c,html",email="wengh7930@gmail.com,current_focus='miniprogram and web development,python scrpy'):
        self.__name=name
        self.__languages=languages
        self.__email=email
        self.__status=Focusing
        self.__current_focus=current_focus
    def get_name(self):
        return self.__name
    def get_languages(self):
        return self.__languages
    def get_email(self):
        return self.__email
    def is_active(self):
        return self.__status
    def get_current_focus(self):
        return self.__current_focus
    def set_languages(self,languages):
        self.__languages=languages
    def set_email(self,email):
        self.__email=email
    def set_active(self,value):
        self.__status=value
    def set_current_focus(self,current_focus):
        self.__current_focus=current_focus
    def __str__(self):
        if self.__status==Focusing:
            return "{} currently developing.".format(self.__name)
        else:
            return "{0} ({1}), {2} - {3}".format(self.__name,self.__languages,self.__email,self.__current_focus)
