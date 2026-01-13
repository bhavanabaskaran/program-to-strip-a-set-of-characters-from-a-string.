# program-to-strip-a-set-of-characters-from-a-string.
def strip_chars(string, chars):
    return "".join(c for c in string if c not in chars)

print("\nOriginal String:")
print("The quick brown fox jumps over the lazy dog.")
print("After stripping a, e, i, o, u:")
print(strip_chars("The quick brown fox jumps over the lazy dog.", "aeiou"))
