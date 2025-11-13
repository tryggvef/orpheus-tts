https://www.youtube.com/watch?v=LD4fmseuLgo&t=1s

Installing uv

curl -LsSf https://astral.sh/uv/install.sh | sh

  32  uv --version
   33  mkdir orpheus-tts
   34  cd orpheus-tts/
   35  uv init

To run notebooks in VS Code, add iPython kernel to your environment.

uv add ipykernel
To use the Jupyter Notebook browser environment with uv simply use

uv run --with jupyter jupyter lab

git config --global user.email t...
git config --global user.name t


git add -A
git commit -m "Initial commit"

git remote add origin https://github.com/tryggvef/orpheus-tts.git
git branch -M master
git push -u origin master  #Not working on ubuntu...