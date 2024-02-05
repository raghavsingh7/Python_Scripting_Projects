import hashlib

def  HashCrack(inputHash):
    try:
        passFile = open("text.txt")
    except:
        print("Could not find file.")

    for password in passFile:
        encPass = password.encode("utf-8")
        digest = hashlib.sha256(encPass.strip()).hexdigest()
        if digest == inputHash:
            print("Password Found: " + password)

if __name__ == '__main__':
    HashCrack("HASH INPUT HERE")
