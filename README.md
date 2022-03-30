# Python-DS
professor = ['Mr. James Ace', 'Ms. Jc Penn', 'Dr. VG', 'Mr. David Sez']

def split_title_and_name(person):
    title = person.split()[0]
    lastname = person.split()[-1]
    return '{} {}'.format(title, lastname)

list(map(split_title_and_name, professor))
