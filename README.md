# BDAP_Dicoding
Bike Sharing
Streamlit Cloud : [Dashboard Proyek] (https://nrazizahmr.streamlit.app/)
## Setup environment
1. Clone this repository
   ```
   git clone https://github.com/nrazizahmr/bdap_dicoding.git
   ```

2. Move to directory bdap_dicoding
   ```
   cd bdap_dicoding
   ```

3. Move to directory Submission
   ```
   cd Submission
   ```
4. Pustaka
   ```
   python -m pip install zlib jpeg libpng
   ```   
4. Buat Virtual Environment:
   ```
   python3 -m venv myenv
   source myenv/bin/activate
   ```
5. Install all the requirements inside "requirements.txt"
   ```
   pip install -r dashboard\requirements.txt
   ```
6. Instal Tanpa Binary (Build dari Source)
   ```
   pip install --no-binary :all: pillow
   ```
7. Run streamlit app
   ```
   streamlit run dashboard\dashboard.py
   ```
