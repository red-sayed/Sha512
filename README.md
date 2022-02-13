# ☝️Sha512 ![](https://img.shields.io/apm/l/vim-mode)

<img src="https://github.com/vladimirrogozin/Sha512/blob/main/Screenshots/sha512_main.png?raw=true" style="object-fit:contain;
            width:auto;
            height:520px;">

## What is it?

This is an implementation and console application of _Sha512_ hash function, one of the most famous hash function. It is a part of [_RedLibrary_](https://github.com/Red-company/RedLibrary).

## How to use?

Function prototype:

```C
// Open functions.
namespace Red {
    /**
     * @brief Sha512
     *
     * @param input Pointer to data to be hashed.
     *
     * @return Pointer to a new string with sha512 hash.
     */
    std::string * Sha512(std::string *input);

    /**
     * @brief Sha512file
     *
     * @param file Pointer to file to be hashed.
     *
     * @return Pointer to a new string with sha512 hash.
     */
    std::string * Sha512file(std::FILE* file);

    /**
     * @brief Sha512file
     *
     * @param filename Pointer to str with filename.
     *
     * @return Pointer to a new string with sha512 hash.
     */
    std::string * Sha512file(const char* filename);
}
```

## What about speed?

Speed test can will be soon, sorry.

## Tech notes:

* It understands all _ASCII_ characters.
* It's rather fast.

## Example:

<img src="https://github.com/vladimirrogozin/Sha512/blob/main/Screenshots/sha512_ex.png?raw=true" style="object-fit:contain;
            width:auto;
            height:520px;">

##
All material in this repository is in the public domain.
