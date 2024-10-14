# Meus-perfil-Web
Será a minha Home Page. Irá direcionar o público para meus links disponíveis.

import pandas as pd
import streamlit as st

st.set_page_config(page_title = "Meu site - Lorena Duarte")

with st.container():
     st.subheader("Meus links")
     st.title("Dashboard de contratos")
     st.write("Informações sobre os contratos fechados pela Prefeitura ao longo de maio")
     st.write("Meu perfil no Instagram! [Clique aqui](https://www.instagram.com/lrn_duarte/)")
     st.write("Minha Newsletter gratuita -> [Clique aqui](https://substack.com/@lorenavaleska)")
     st.write("Meu Git Hub -> [Clique aqui] (https://github.com/LrnDuarte)")

with st.container():
        st.write("---")
