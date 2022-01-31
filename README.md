# NFT Color Pixel
This project was developed in python programming language and numpy, random and Image libraries are used. When the program is run, it generates 696 different random png images. The number 696 is obtained by multiplying the ASCII values of the letters N,F,T and the length of the "RGB" string expression. </br></br>
TOTAL_SUPPLY = ASCII('N') * ASCII('F') * ASCII('T') * LENGTH("RGB") </br></br>
The edges of the NFT lettering are left fixed with black color. The inner filling of the NFT text was randomly determined once for each picture and applied to the entire inner filling. A random color is generated for each pixel on the outside of the NFT text. </br></br>
The program calculates a special COLOR_AVARAGE average number for each NFT it produces. R, G, B values in each pixel are summed and divided by 3, and the all total is found by applying it for all pixels. The total value found is calculated by dividing the power of the TOTAL_SUPPLY constant. COLOR_AVARAGE value makes each NFT COLOR PIXEL NFT different from each other and serves as an identity. </br></br>
When the development was completed, the first 696 different NFTs produced by the program were offered for sale on OpenSea. The floor price for NFTs is inspired by the unique COLOR_AVARAGE number for each image. </br></br>
Note: The site header was uniquely generated using the same methods. </br>
