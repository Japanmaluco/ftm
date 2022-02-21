# Mint-collection-nft-using-Metaplex-and-Solana

`git clone https://github.com/Japanmaluco/ftm`
`cd ftm`
`yarn install`
`yarn start`

# To deploy your nft collection, using candy machine v2 tutorial (https://docs.metaplex.com/candy-machine-v2/getting-started)
`ts-node ~/metaplex/js/packages/cli/src/candy-machine-v2-cli.ts upload \                            
    -e devnet \
    -k ~/.config/solana/devnet.json \
    -cp config.json \
    -c example \
    ./assets`
    
`ts-node ~/metaplex/js/packages/cli/src/candy-machine-v2-cli.ts verify_upload \                     
    -e devnet \
    -k ~/.config/solana/devnet.json \
    -c example`
    
`ts-node ~/metaplex/js/packages/cli/src/candy-machine-v2-cli.ts mint_one_token \                    
    -e devnet \
    -k ~/.config/solana/devnet.json \
    -c example`
