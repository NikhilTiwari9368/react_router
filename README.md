.....______..... Router is a library that allows you to manage and navigate between different views or components in your application based on the URL. The most popular routing library for React is React Router.   

<!-- 
..... outlet :---- An Outlet should used in parent route elements to render their chiuld route elements. This allows nested UI to Show up when child routes are rendered. if the parent route matched exaclty, it will render a child index route or nothing if there is no index route..... 


<!-- <NavLink to="/" className={({ isActive}) => isActive ? "nav-link active" : "nav-link" }> Home <NavLink /> --> 

<!-- NavLink is used for define the link or make the active link in the navigation bar.... 

///// React Native //////  
 -->

<!---- NavLink to="/about" style={({isActive}) => return { color: isActive ? "red" : "black",}; 
}> 
about 
<NavLink/> 


<!------- HOW TO CREATE A ErrorPage in React >

<!----- useNAVIGATE HOOK IN RR ------!> 
<!--- useNavigate ---!> 
import { useNavigate } from react-route-dom ;



In the error page there is some other page also:

const error = useRouteErro();
const navigate = useNavigate();

<!--  navigation.state... --> 
<!-- idle - There is no navigation pending.. 
submitting- A router action is being called due to a form submission using POST,PUT,PATCH,DELETE
loading- The loaders for the next routers are bring called to render the next page......-->

<!-- to secure the api key from the outside world so we use the .env file.... --> 
<!----->#   r e a c t _ r o u t e r  
 