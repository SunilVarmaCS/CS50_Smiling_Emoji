def main():
    #user input
    all_happy = input()

    #use convert function
    sad = convert(all_happy)

    #print the sad man
    print(sad)

def convert(all_happy):
    #use replace method for all_happy
    one_happy = all_happy.replace(":)", '🙂' )
    two_happy = one_happy.replace(":(", '🙁' )

    #return happy
    return two_happy

main()
