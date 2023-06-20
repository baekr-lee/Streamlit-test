import streamlit as st
st.title('부산대 경영 분석동아리 IBA')
col1,col2 = st.columns([2,3])

with col1 :
    st.subheader('IBA동아리 회원 명단')

with col2 :
    st.subheader('동아리 활동')

tab1, tab2= st.tabs(['재욱' , '재현'])
st.sidebar.title('IBA 활동내역')
option = st.sidebar.selectbox(
    'Menu',
     ('재욱', '재현', '설지'))
