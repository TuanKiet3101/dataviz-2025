Thiết lập môi trường DataViz gồm Anaconda, Python 3.11, thư viện (pandas, numpy, matplotlib, seaborn, jupyter), Git & GitHub, VS Code. 
Các bước đã thực hiện
Tạo môi trường:
conda create -n dataviz python=3.11
conda activate dataviz
Cài thư viện:
pip install pandas numpy matplotlib seaborn jupyter
Chạy Jupyter Notebook:
jupyter notebook
3. Lỗi gặp và cách sửa

 Conda activate không hoạt động (PowerShell)
Lỗi: CommandNotFoundError
Cách sửa:
conda init powershell
Sau đó restart terminal và chạy lại conda activate dataviz

Jupyter không chạy được
Lỗi: 'jupyter' is not recognized
Cách sửa:
pip install notebook
hoặc:
python -m notebook
4. Kết quả
Environment dataviz hoạt động OK
Cài đủ thư viện: pandas, numpy, matplotlib, seaborn, jupyter
Jupyter Notebook chạy được
GitHub repo đã tạo và push thành công

