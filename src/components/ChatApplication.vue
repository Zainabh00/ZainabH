<template>
    <div class="layout">
      <div class="sidebar">
        <div class="sidebar-header">
          <img src="@/assets/Logo.svg" alt="logo" class="logo" />
          <span class="team-text">Hi TEAM</span>
        </div>
        <ul class="menu">
          <li class="menu-item active">
            <i class="bi bi-house-door-fill"></i>
            <span>Dashboard</span>
          </li>
          <li class="menu-item">
            <i class="bi bi-box-fill"></i>
            <span>Orders</span>
          </li>
          <li class="menu-item">
            <i class="bi bi-people"></i>
            <span>Passengers</span>
          </li>
          <li class="menu-item">
            <i class="bi bi-bus-front"></i>
            <span>Captains</span>
          </li>
        
          <li class="menu-item">
            <i class="bi bi-card-checklist"></i>
            <span>Categories</span>
          </li>
          <hr />

          <li class="menu-item">
            <i class="bi bi-card-text"></i>
            <span>Settlement</span>
          </li>
          <li class="menu-item">
            <i class="bi bi-wechat"></i>
            <span>Contact</span>
          </li>
          <li class="menu-item">
            <i class="bi bi-stars"></i>
            <span>Reviews</span>
          </li>
          <hr />

          <li class="menu-item">
            <i class="bi bi-shield-shaded"></i>
            <span>Permissions</span>
            <i class="bi bi-chevron-down"></i>
          </li>
          <li class="menu-item">
            <i class="bi bi-translate"></i>
            <span>Translation</span>
          </li>
          <li class="menu-item">
            <i class="bi bi-film"></i>
            <span>Education Video</span>
          </li>
          <li class="menu-item">
            <i class="bi bi-gear"></i>
            <span>Settings</span>
          </li>
          <li class="menu-item">
            <i class="bi bi-dice-6-fill"></i>
            <span>Content</span>
          </li>
        </ul>
      </div>
      <div class="main-content">
        <nav class="navbar">
          <div class="grid d-flex gap-3">
            <i class="bi bi-search"></i>
            <i class="bi bi-ui-radios-grid"></i>
          </div>
          <div class="grid d-flex gap-3">
            <i class="bi bi-moon"></i>
            <i class="bi bi-bell"></i>
            <img src="@/assets/Flag.jpeg" alt="flag" class="flag" style="width: 30px;">
            <img src="@/assets/user-11.jpg" alt="user" class="user" style="width: 30px;">
          </div>
        </nav>
        <div class="content ">
          <div class="row">
      <div class="navbar navbar-expand-lg bg-body-tertiary custom-navbar">
        <div class="container-fluid d-flex justify-content-between align-items-center">
          <a class="navbar-brand">Chat</a>         
          <div class="d-flex align-items-center gap-3">
            <i class="bi bi-house"> /</i>
            <button class="btn custom-btn btn-sm" type="submit">Chat</button>
          </div>
        </div>
      </div>
    </div>
 <div class="chat-container ">
    <div class="contacts-column">
      <div class="profile">
        <img src="@/assets/Mathew.svg"  alt="User Profile">
        <div class="profile-info">
          <h3>Mathew Anderson</h3>
          <p>Marketing Director</p>
        </div>
        <div class="more-button">...</div>
      </div>
      <div class="search-bar p-2">
          <div class="input-group input-group-sm">
            <span class="input-group-text bg-white border-end-0 py-1"><i class="bi bi-search small"></i></span>
            <input type="text" class="form-control form-control-sm border-start-0 py-1" placeholder="Search contacts" />
          </div>
        </div>
      <div class="recent-chats">
        <span>Recent Chats</span>
        <span>▼</span>
      </div>
      <div class="contacts-list">
        <div class="contact">
          <img src="@/assets/Michell Flintoff.svg" alt="Contact"> 
          <div class="contact-info">
            <div class="name">Michell Flintoff</div>
            <div class="message">You: Yesterday was great...</div>
          </div>
          <div class="time">15 minutes</div>
        </div>
        <div class="contact">
          <img src="@/assets/Bia.svg" alt="Contact">
          <div class="contact-info">
            <div class="name">Bianca Anderson</div>
            <div class="message">Nice looking dress you...</div>
          </div>
          <div class="time">30 minutes</div>
        </div>
        <div class="contact ">
          <img src="@/assets/Andrew.svg" alt="Contact">
          <div class="contact-info">
            <div class="name">Andrew Johnson</div>
            <div class="message">Sent a photo</div>
          </div>
          <div class="time">2 hours</div>
        </div>
        <div class="contact">
          <img src="@/assets/mark.svg" alt="Contact">
          <div class="contact-info">
            <div class="name">Mark Strokes</div>
            <div class="message">Lorem ipsum text sud...</div>
          </div>
          <div class="time">5 days</div>
        </div>
        <div class="contact">
           <img src="@/assets/m.svg" alt="Contact"> 
          <div class="contact-info">
            <div class="name">Mark, Stoinus & Rishvi..</div>
            <div class="message">Lorem ispusm text ....</div>
          </div>
          <div class="time">5 days</div>
        </div>
        <div class="contact">
          <img src="@/assets/Bia.svg" alt="Contact">
          <div class="contact-info">
            <div class="name">Bianca Anderson</div>
            <div class="message">Nice looking dress you...</div>
          </div>
          <div class="time">30 minutes</div>

        </div>
      </div>
    </div> 
    <div class="divider"></div>
    <div class="chat-column">
      
      <div class="chat-header">
        <img src="@/assets/away.svg" alt="Contact">
        <div class="chat-header-info">
          <p>Away</p>
        </div>
        <div class="chat-header-actions">
          
         <button><i class="bi bi-ban"  style="color: #635BFF;"></i></button> 
          <button><i class="bi bi-trash3" style="color: red;" ></i></button>
          <button><i class="bi bi-telephone" style="color: #29343D;"></i></button>
          <button><i class="bi bi-camera-video" style="color: #29343D;"></i></button>
          <button>≡</button> 
        </div>
      </div>
      <div class="horizontal-divider"></div>
      <div class="messages">
        <div>  <img src="@/assets/user8.svg" style="width: 40px; height: 40px;" >  
          <span class=" time-ago">Andrew, 2 hours ago</span>
          </div>
        <div class="message received" style= "background: #EFF4FA;">
          <p>If I don't like something, I'll stay away from it.</p>
          
        </div>
        <div class="message-container">
  <div class="time-ago">2 hours ago</div>
  <div class="message sent">
    <p>If I don't like something, I'll stay away from it.</p>
  </div>
</div>
        <div>  <img src="@/assets/user8.svg" style="width: 40px; height: 40px;" >    <span class=" time-ago">Andrew, 2 hours ago</span>
        </div> 
        <div class="message received" style= "background: #EFF4FA;">
          <p>I want more detailed information.</p>
        
        </div>
        <div class="message-container">
  <div class="time-ago">2 hours ago</div>
  <div class="message sent">
    <p>If I don't like something, I'll stay away from it</p>
  </div>
</div>
<div class="message-container">
  <div class="message sent">
    <p>They got there early, and they got really good seats</p>
  </div>
</div>
<div>  <img src="@/assets/user8.svg" style="width: 40px; height: 40px;" >   <span class=" time-ago">Andrew, 2 hours ago</span>
</div>
<div class="message-container">
  <div class="message received">
  <img src="@/assets/soewt.svg" alt="Image" class="message-image" style=" left: 11px; ;">
  <div class="message received">
  </div>
  </div>
      </div>
      </div>
      <div class="horizontal-divider"></div>
      <div class="chat-footer">
        <button><i class="bi bi-emoji-smile"></i></button>
        <input type="text" placeholder="Type a Message"> 
        <button class="btn btn-warning mt-3" data-bs-toggle="modal" data-bs-target="#blockUserModal">
      <i class="bi bi-image"></i> 
    </button>
    <div class="modal fade" id="UnblockUserModal" tabindex="-1" aria-labelledby="UnblockUserLabel" aria-hidden="true">
      <div class="modal-dialog modal-dialog-centered">
        <div class="modal-content text-center p-4">
          <div class="modal-header border-0">
            <h5 class="modal-title w-100" id="UnblockUserLabel">
              <i class="bi bi-unlock-fill text-primary" style="font-size: 24px;"></i>
              <br>Unlock User
            </h5>
          </div>
          <div class="modal-body">
            <p>You are going to unblock this user, are you sure?</p>
          </div>
          <div class="modal-footer border-0 d-flex justify-content-center">
            <button type="button" class="btn btn-secondary custom-btn" data-bs-dismiss="modal">Cancel</button>
            <button type="button" class="btn btn-warning custom-btn">Yes</button>
          </div>
        </div>
      </div>
    </div>
        <button class="btn btn-warning mt-3" data-bs-toggle="modal" data-bs-target="#DeleteConversation">
      <i class="bi bi-paperclip"></i> 
    </button>
    <div class="modal fade" id="DeleteConversation" tabindex="-1" aria-labelledby="DeleteConversation" aria-hidden="true">
      <div class="modal-dialog modal-dialog-centered">
        <div class="modal-content text-center p-4">
          <div class="modal-header border-0">
            <h5 class="modal-title w-100" id="DeleteConversation">
              <i class="bi bi-trash3-fill text-primary" style="font-size: 24px;"></i>
              <br>Delete Conversation
            </h5>
          </div>
          <div class="modal-body">
            <p>Once You Sure To Delete This Conversation , You Will Not Be Able To Undo This Action</p>
          </div>
          <div class="modal-footer border-0 d-flex justify-content-center">
            <button type="button" class="btn btn-secondary custom-btn" data-bs-dismiss="modal">Cancel</button>
            <button type="button" class="btn btn-warning custom-btn">Yes</button>
          </div>
        </div>
      </div>
    </div>
    <button class="btn btn-warning mt-3" data-bs-toggle="modal" data-bs-target="#blockUserModal">
      <i class="bi bi-mic"></i> 
    </button>
    <div class="modal fade" id="blockUserModal" tabindex="-1" aria-labelledby="blockUserLabel" aria-hidden="true">
      <div class="modal-dialog modal-dialog-centered">
        <div class="modal-content text-center p-4">
          <div class="modal-header border-0">
            <h5 class="modal-title w-100" id="">

              <i class="bi bi-ban text-primary" style="font-size: 24px;"></i>
              <br>Block User
            </h5>
          </div>
          <div class="modal-body">
            <p>You are going to block this user, are you sure?</p>
          </div>
          <div class="modal-footer border-0 d-flex justify-content-center">
            <button type="button" class="btn btn-secondary custom-btn" data-bs-dismiss="modal">Cancel</button>
            <button type="button" class="btn btn-warning custom-btn">Yes</button>
          </div>
        </div>
      </div>
    </div>
      </div>
    </div>
    <div class="divider"></div>
    <div class="media-column">
      
        <div class="media-section">
          <h3>Media <span>(36)</span></h3>
          <div class="media-grid">
            <div class="media-item">
              <img src="@/assets/soewt.svg" alt="Media">
            </div>
            <div class="media-item">
              <img src="@/assets/cap.svg" alt="Media">
            </div>
            <div class="media-item">
              <img src="@/assets/phone.svg" alt="Media">
            </div>
            <div class="media-item">
              <img src="@/assets/mic.svg" alt="Media">
            </div>
            <div class="media-item">
              <img src="@/assets/soewt.svg" alt="Media">
            </div>
            <div class="media-item">
              <img src="@/assets/cap.svg" alt="Media">
            </div>
          </div>
        </div>
        <div class="media-section">
          <h3>Files <span>(36)</span></h3>
          <div class="files-list">
            <div class="file-item">
             <img src="@/assets/sev.svg" alt="sev">
              <div class="file-info">
                <h4>  service-task.pdf</h4>
                <p>2 MB  2 Dec 2022</p>
              </div>
            </div>
            <div class="file-item">
              <img src="@/assets/figma.svg" alt="sev">
              <div class="file-info">
                <h4>homepage-design.fig</h4>
                <p>2 MB  2 Dec 2022</p>
              </div>
            </div>
            <div class="file-item">
              <img src="@/assets/go.svg" alt="sev">
              <div class="file-info">
                <h4>about-us.html</h4>
                <p>2 MB  2 Dec 2022</p>
              </div>
            </div>
            <div class="file-item">
              <img src="@/assets/zip.svg" alt="sev">
              <div class="file-info">
                <h4>work-project.zip</h4>
                <p>2 MB  2 Dec 2022</p>
              </div>
            </div>
            <div class="file-item">
              <img src="@/assets/jav.svg" alt="sev">
              <div class="file-info">
                <h4>custom.js</h4>
                <p>2 MB  2 Dec 2022</p>
              </div>
            </div>
          </div>
        </div>
      </div>  
    </div>
      </div>
  </div>
 </div>
  
  </template>
    <style scoped>
 

* {
  scrollbar-width: none; 
  -ms-overflow-style: none; 
}
::-webkit-scrollbar {
  display: none; 
}

.layout {
  display: flex;
  height: 100vh;
  width: 100%;
}
.main-content {
  flex-grow: 1;
  display: flex;
  flex-direction: column;
  height: 100%; 
}
.content {
  flex-grow: 1;
  padding: 20px;
  background-color: #F4F7FB;
}
.chat-container {
  display: flex;
 
  background-color: white;
  border-radius: 8px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.05);
}
.contacts-column {
  width: 25%;
  overflow-y: auto;
  display: flex;
  flex-direction: column;
  padding: 15px;
}
.chat-column {
  width: 25%;
  display: flex;
  flex-direction: column;
  padding: 15px;
  overflow: visible; 
}
.media-column {
  width: 25%;
  padding: 15px;
  overflow: visible; 
}
.sidebar {
  height: 200px;
  width: 200px;
  background: #FFFFFF;
  padding: 10px;
  display: flex;
  flex-direction: column;
}
.sidebar-header {
  display: flex;
  align-items: center;
  margin-bottom: 20px;
}
.logo {
  width: 40px;
  margin-right: 10px;
}
.menu {
  list-style: none;
  padding: 0;
}
.menu-item {
  display: flex;
  align-items: center;
  padding: 10px;
  cursor: pointer;
  border-radius: 5px;
  transition: background 0.3s;
}
.menu-item:hover,
.menu-item.active {
  background: #635BFF;
  color: white;
}
.menu-item i {
  margin-right: 10px;
}
.content {
    flex-grow: 1;
    padding: 45px;
    background-color: #F4F7FB;
  }.custom-btn {
    background: #FFFFFF;
    color: #635BFF;
    border: none;
  }
  .custom-btn:hover {
    background: #5048cc; 
  }
  .custom-navbar {
    padding: 8px 16px;
    background-color: #FFFFFF;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.05);
    margin-bottom: 16px;
  }
  
  .navbar-brand {
    font-size: 16px;
    font-weight: bold;
    
  } .custom-btn {
    background: #DDDBFF;
    color: #635BFF;
    border: none;
  }
  
  .custom-btn:hover {
    background: #5048cc;
    color: white;
  }.custom-navbar {
  padding: 8px 16px;
  background-color: #fff;
  border-radius: 8px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.05);
  margin-bottom: 16px;
}

.navbar-brand {
  font-size: 16px;
  font-weight: bold;
}

.bi-house {
  font-size: 14px;
  color: #6c757d;
}


.chat-container {
  display: flex;
  height: 100%;
  background-color: white;
  border-radius: 8px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.05);
}

.contacts-column {
  width: 30%;
  border-right: 1px solid #FFFFFF;
  overflow-y: auto;
  display: flex;
  flex-direction: column;
  padding: 15px;
}
.profile {
  display: flex;
  padding: 15px;
  border-bottom: 1px solid #ffff;
  position: relative;
  align-items: center;
}

/* .profile img {
  width: 40px;
  height: 40px;
  border-radius: 50%;
  margin-right: 10px;
  object-fit: cover;
}    */

.profile-info {
  flex-grow: 1;
}

.profile-info h3 {
  font-size: 14px;
  margin: 0;
  font-weight: 600;
}

.profile-info p {
  font-size: 12px;
  color: #888;
  margin: 0;
}

.more-button {
  font-size: 18px;
  color: #888;
  cursor: pointer;
}

.recent-chats {
  padding: 12px 15px;
  color: #888;
  font-size: 13px;
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.contacts-list {
  overflow-y: auto;
  flex-grow: 1;
}

.contact {
  display: flex;
  padding: 12px 15px;
  border-bottom: 1px solid #f5f5f5;
  cursor: pointer;
  align-items: center;
  position: relative;
}

.contact:hover {
  background-color: #f9f9f9;
}

/* .contact img {
  width: 40px;
  height: 40px;
  border-radius: 50%;
  margin-right: 10px;
  object-fit: cover;
}  */

.contact-info {
  flex-grow: 1;
  overflow: hidden;
}

.contact-info .name {
  font-size: 14px;
  margin-bottom: 2px;
  font-weight: 500;
}

.contact-info .message {
  font-size: 12px;
  color: #888;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
}

.contact .time {
  font-size: 11px;
  color: #888;
  white-space: nowrap;
  align-self: flex-start;
  margin-top: 2px;
}

.contact.active {
  background-color: #f0f0ff;
}

.chat-container {
  display: flex;
  height: 100%;
  background-color: white;
  border-radius: 8px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.05);
}
/* .contact img {
  width: 40px;
  height: 40px;
  border-radius: 50%;
  margin-right: 10px;
  object-fit: cover;
} */
.divider {
  width: 1px;
  background-color: #E0E6EB;
  height: 100%;
}
.chat-column {
  width: 50%;
  display: flex;
  flex-direction: column;
  border-right: 1px solid #FFFFFF;
  padding: 15px;
  overflow: visible; /* ضمان عرض كامل للمحتوى */
}

.chat-header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  /* padding: 12px 15px; */
  border-bottom: 1px solid #FFFFFF;
  background-color: #ffff;
}

.chat-header-user {
  display: flex;
  align-items: center;
}
.horizontal-divider {
  width: 100%;
  height: 1px;
  background-color: #E0E6EB;
  margin: 5px 0; /* مسافة من الأعلى والأسفل */
  position: container;
}


.user-info {
  display: flex;
  align-items: center;
  gap: 8px; /* مسافة بين الصورة والنص */
  font-size: 14px;
  color: #333;
}

.user-avatar {
  width: 40px;
  height: 40px;
  border-radius: 50%; /* يجعل الصورة دائرية */
}

.time-ago {
  font-size: 12px;
  color: gray;
}
.user-avatar {
  position: relative;
  margin-right: 10px;
} 

.user-avatar img {
  width: 40px;
  height: 40px;
  border-radius: 50%;
  object-fit: cover;
} 

.chat-header-info {
  flex-grow: 1;
}

.chat-header-info h3 {
  font-size: 14px;
  margin: 0;
  font-weight: 600;
}

.chat-header-info p {
  font-size: 12px;
  color: #888;
  margin: 0;
}

.chat-header-actions {
  display: flex;
  gap: 12px;
}

.chat-header-actions button {
  background: none;
  border: none;
  cursor: pointer;
  color: #888;
  font-size: 16px;
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 0;
}

 .messages {
  flex-grow: 1;
  padding: 15px;
  overflow-y: auto;
  background-color: #FFFFFF;
  display: flex;
  flex-direction: column;
}

 .message-timestamp {
  display: flex;
  align-items: center;
  font-size: 12px;
  color: #888;
  margin: 10px 0;
} 

.message-avatar {
  width: 24px;
  height: 24px;
  border-radius: 50%;
  margin-right: 8px;
} 

.message {
  margin-bottom: 10px;
  max-width: 70%;
  padding: 10px 12px;
  border-radius: 15px;
  position: relative;
  line-height: 1.4;
}

.message p {
  margin: 0;
  font-size: 13px;
}

.message-time {
  font-size: 11px;
  color: #888;
  margin-top: 3px;
  text-align: right;
} 

  .received {
  align-self: flex-start;
  color: #333;
  border-bottom-left-radius: 4px;
}  
.received-image {
background:none ;
} 

.message-container {
  display: flex;
  flex-direction: column;
  align-items: flex-end; 
} 
.time-ago {
  font-size: 12px;
  color: gray;
  margin-bottom: 4px; /* مسافة بين الوقت والرسالة */
}

 .message.sent {
  background-color: #ECFDFD;
  padding: 10px;
  border-radius: 10px;
  max-width: 60%;
} 

.horizontal-divider {
  width: 100%;
  height: 1px;
  background-color: #E0E6EB;
  margin: 0px 0; /* مسافة من الأعلى والأسفل */
  position: container;
}

.chat-footer {
  display: flex;
  align-items: center;
  gap: 6px;
  padding: 5px 10px;
} 

 .chat-footer button {
  padding: 5px;
  border: none;
  background: none;
  outline: none;
} 

 .chat-footer input {
  flex: 1;
  padding: 6px 10px;
  border: 1px solid #ddd;
  border-radius: 20px;
  outline: none;
} 

.chat-footer input {
  border: none;
  background: none;
  outline: none;
  color: transparent;
  caret-color: black;
} 
.divider {
  width: 1px;
  background-color: #E0E6EB;
  height: 100%;
}
/* Media column */
.media-column {
  width: 25%;
  padding: 15px;
  overflow: visible;
}

.media-section {
  margin-bottom: 24px;
}

.media-section h3 {
  font-size: 14px;
  margin-bottom: 12px;
  color: #333;
  font-weight: 600;
}

.media-section span {
  color: #888;
  font-size: 12px;
  margin-left: 4px;
  font-weight: normal;
}

.media-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 8px;
}

.media-item {
  height: 70px;
  border-radius: 8px;
  overflow: hidden;
  background-color: #f5f5f5;
}

.media-item img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.files-list {
  display: flex;
  flex-direction: column;
  gap: 8px;
}

.file-item {
  display: flex;
  align-items: center;
  gap: 15px;
  padding: 10px;
  border-radius: 8px;
  transition: background 0.3s ease;
}

.file-item:hover {
  background: #f5f5f5;
}

.file-item img {
  width: 40px;
  height: 40px;
  object-fit: contain;
}

.file-info h4 {
  margin: 0;
  font-size: 16px;
}

.file-info p {
  margin: 4px 0 0;
  font-size: 12px;
  color: gray;
}

.modal-content {
  border-radius: 12px;
  border: none;
}

.btn-primary {
  background-color: #635BFF;
  border-color: #635BFF;
  
} 
.icon-size {
  font-size: 24px;
}
.modal-footer .custom-btn {
  min-width: 100px;
  padding: 10px 20px;
  font-size: 16px;
  border-radius: 8px;
}
.modal-content {
  border-radius: 12px;
  box-shadow: 0px 4px 15px rgba(0, 0, 0, 0.1);
}

.modal-body p {
  font-size: 18px;
  color: #333;
}
.btn-secondary {
  background-color: #6c757d;
  border: none;
}
.btn-primary {
  background-color: #635BFF;
  border: none;
}
.btn-danger {
  background-color: #5935dc;
  border: none;
}

.btn-warning {
  background-color: #575CD4;
  border: none;
  color: #212529;
}

    </style> 