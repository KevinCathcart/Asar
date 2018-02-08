from os import environ

env = Environment(ENV = {'TERM': environ['TERM'],'PATH': environ['PATH']},
                  CPPFLAGS = ['-Dlinux',
                              '-DINTERFACE_CLI',
                              '-Dstricmp=strcasecmp'])

env.Program('asar', Glob('src/*.cpp'))
