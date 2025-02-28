import streamlit as st

background_image_url = "https://www.pixelstalk.net/wp-content/uploads/2016/07/Desktop-cars-full-hd-wallpapers-1080p-download.jpg"

st.markdown(
    f"""
    <style>
    .stApp {{
        position: relative;
        min-height: 200vh;
    }}
    
    .stApp::before {{
        content: "";
        position: absolute;
        top: 0;
        left: 0;
        right: 0;
        bottom: 0;
        background-image: url("{background_image_url}");
        background-size: cover;
        background-position: center;
        background-repeat: no-repeat;
        opacity: 0.3;   
    }}
    main 
    {{
        background-color: rgba(255, 255, 255, 0);  
        padding: 20px;
        border-radius: 10px;
    }}
    .stTitle, .stText, .stCheckbox, .stButton, .stChatInput
    {{
        color: #000000;  
    }}
     .stChatInput 
     {{
        position: fixed;
        bottom: 20px; 
        left: 50p%;
        transform: translateX(-50%)  
        width: 90%;  
        z-index: 9999; 
    </style>
    """,
    unsafe_allow_html=True
)
st.title("Welcome to my world!")

st.title("😉 Hello friend😉 \n Test your luck")
option = st.radio("Pick one of the following options:",
    ("1", "2", "3") 
)

image_width = 100
if option == "1":
    st.image("https://thumbs.dreamstime.com/b/laughing-buddha-cute-statue-traditional-chinese-feng-shui-displayed-garden-chinese-new-year-85626166.jpg")
    audio_file = "https://drive.google.com/file/d/1IKGWuJEvuYHd4RSlkS5cBHaPfCRwAKLo/view?usp=sharing"
    st.audio(audio_file)
elif option == "2":
    st.image("https://th.bing.com/th/id/R.10a7e668ba1c5e03114e57c87c841079?rik=o55MjB5UUC6fbQ&pid=ImgRaw&r=0")
    audio_file = "https://drive.google.com/file/d/1n-6ZgejMFkgXOSQ85mEzJJN01Jl2lsdU/view?usp=sharing"
    st.audio(audio_file)
else:
    st.image("https://resize.indiatvnews.com/en/resize/newbucket/1200_-/2017/04/blast-representational-pic-1493099766.jpg")
    audio_file = "https://drive.google.com/file/d/1E0brJIlDCDwWLNyknWI6j1rEMC07PbZH/view?usp=sharing"
    st.audio(audio_file)

st.chat_input("How was your day Nandu?")
st.chat_message("user").text("Hello Nandu, how can I help you today?")
