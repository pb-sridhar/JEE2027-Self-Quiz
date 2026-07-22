# Create a LICENSE file
echo "MIT License" > LICENSE

# Create a .gitignore
echo "node_modules/" > .gitignore
echo ".DS_Store" >> .gitignore

git add README.md LICENSE .gitignore
git commit -m "Add project documentation"
git push origin main
