def is_anagram(word1, word2):
    clean1 = sorted(word1.replace(" ", "").lower())
    clean2 = sorted(word2.replace(" ", "").lower())
    return clean1 == clean2

if __name__ == "__main__":
    a = "listen"
    b = "silent"
    print(f"{a} and {b} are anagrams: {is_anagram(a, b)}")
